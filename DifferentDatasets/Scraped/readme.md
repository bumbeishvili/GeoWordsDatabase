# Bottom is a story of gathering this words info

p.s. Links are not working,all contents were copied from webArchive and it's only for informational purposes

All credits - [Giorgi Jvaridze](#0xh3x)

<div class="post-frame">
            
            
            
          <div id="articles">
            
              <article class="post clearfix" id="post_71533514">
                <header>
                    
                    
                        <h1><a href="/web/20130524144932/http://blog.giorgijvaridze.com/71533514">ყველაზე ხშირად გამოყენებადი სიტყვები ქართულში</a></h1>
                    
                    
      	        
            
              
    
                </header>
                <div class="body">
                  <div class="inner">
                    <p>გადავწყვიტე დავითვალო ყველაზე ხშირად ხმარებადი სიტყვები ქართულში.<br>ამისათვის ორი რამეა საჭირო დიდი მოცულობის ქართული ტექსტი (Text Corpus)&nbsp;და სისტემა რომელიც დაამუშავებს ამ ტექსტს.</p>
<p>ტექსტის შეგროვება ინტერნეტიდან შეიძლება, მაგრამ უნდა გავითვალისწინოთ ის ფაქტი რომ&nbsp;ინტერნეტიდან შეგროვებული ტექსტი არის "დაბალი ხარისხის" (სლენგი, სპამი და ა.შ.) და ქართულ ენას არ ასახავს ბოლომდე.&nbsp;თუმცა ამ შემთხვევაში ტექსტის ხარისხი დამაკმაყოფილებელია.</p>
<p>&nbsp;</p>
<p><span style="font-size: medium;">მონაცემების შეგროვება</span></p>
<p>მთლიანი ჯინეტის გადმოწერას და დამუშავებას დიდი დრო სჭირდება ამიტომ მხოლოდ რამოდენიმე საიტიდან შევაგროვებ ტექსტს.<br>პირველი საიტი რაც მომაფიქრდა არის ქართული ვიკიპედია. ვიკიპედია პერიოდულად აქვეყნებს თავის მონაცემთა ბაზას <a href="/web/20130524144932/http://dumps.wikimedia.org/">http://dumps.wikimedia.org/</a> -ზე xml ფორმატში რაც საკმაოდ გვიადვილებს ამოცანას.</p>
<p><a href="/web/20130524144932/http://buki.ge/library-list.html">http://buki.ge/library-list.html</a> -ზე არის სხვადასხვა ცნობილი ნაწარმოებების ტექსტები<br><a href="/web/20130524144932/http://lib.ge/">http://lib.ge/</a> არის საიტი სადაც მწერლები და პოეტები თავიანთ ნაწარმოებებს ტვირთავენ.<br><a href="/web/20130524144932/http://www.nplg.gov.ge/dlibrary/">http://www.nplg.gov.ge/dlibrary/</a> არის საქართველოს პარლამენტის ეროვნული ბიბლიოთეკის ციფრული ბიბლითეკა. სადაც სხვადასხვა სამეცნიერო ნაშრომები, დისერტაციები და სხვა სახის ტექსტებია.<br>და ბოლოს <a href="/web/20130524144932/http://forum.ge/">http://forum.ge/</a> თბილისის ფორუმი. ქართულ ინტერნეტში ყველაზე პოპულარული ფორუმი.</p>
<p>&nbsp;</p>
<p>ვებ გვერდებიდან ტექსტების შესაგროვებლად გამოვიყენებ scrapy-ს (<a href="/web/20130524144932/http://scrapy.org/)">http://scrapy.org/)</a> პითონის web crawling framework-ს (ქართულად როგორ ითარგმნება არ ვიცი :)). ყველა საიტისთვის, გარდა ვიკიპედიასთვის, შექმნილი მაქვს scrapy პროექტი. crawler-ის გაშვება ხდება ამ ბრძანებით: scrapy crawl &lt;url&gt; სადაც &lt;url&gt; არის ის მისამართი რაც პროექტში გვაქვს გაწერილი.&nbsp;</p>
<p>&nbsp;</p>
<p>დავაყენოთ scrapy<br><script src="/web/20130524144932js_/https://gist.github.com/1232910.js"></script><link rel="stylesheet" href="/web/20150824145339/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232910" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">sudo apt-get install python-scrapy</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232910/raw/670adff25a03e30cebafc7faa8acf047d7dad287/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232910#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145339/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>გამოყენებული კოდი შეგიძლიათ ნახოთ გიტჰაბზე <a href="/web/20130524144932/https://github.com/0xh3x/kacorpus">https://github.com/0xh3x/kacorpus</a></p>
<p>პირველ რიგში გადმოვიწეროთ და დავამუშაოთ ვიკიპედიას მონაცემები.<br>xml-ის დასამუშავებლად ვიყენებ cElementTree მოდულს რომელიც <a href="/web/20130524144932/http://effbot.org/zone/celementtree.htm#benchmarks">http://effbot.org/zone/celementtree.htm#benchmarks</a> ამ benchmark-ის მიხედვით სხვა მოდულებთან შედარებით სწრაფია და ნაკლებ მეხსიერებასაც მოიხმარს.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232912.js"></script><link rel="stylesheet" href="/web/20150824145339/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232912" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> wiki/</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">wget <span class="pl-s"><span class="pl-pds">"</span>/web/20150824145339/http://dumps.wikimedia.org/kawiki/latest/kawiki-latest-pages-meta-current.xml.bz2<span class="pl-pds">"</span></span></td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">bunzip2 kawiki-latest-pages-meta-current.xml.bz2</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">python wikidump2text.py kawiki-latest-pages-meta-current.xml ../wikitext.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232912/raw/dd36f313b19165dc2ce96ffe08de1d986091a30d/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232912#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145339/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>შემდეგ გადმოვიწეროთ buki.ge-დან. buki.ge-ზე ტექსტები არის .doc ფორმატში. .doc-დან ტექსტურ ფორმატში გადასაყვანად გამოვიყენებთ antiwords-ს.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232915.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232915" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> ../bukige</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">scrapy crawl buki.ge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">sudo apt-get install antiword</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">antiword <span class="pl-k">*</span>.doc<span class="pl-k">&gt;</span>../bukigetext.txt</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-gistfile1-sh-LC5" class="blob-code blob-code-inner js-file-line">rm <span class="pl-k">*</span>.doc</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232915/raw/974f7f7100397e082071f65b71d03f9efb7f1abf/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232915#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>იგივეს ვაკეთებთ nplg.gov.ge-თვის. ოღონდ ამჯერად pdf ფალები გადაგვყავს ტექსტ ფაილებში.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232918.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232918" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> ../nplggovge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">scrapy crawl nplg.gov.ge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">sudo apt-get install poppler-utils</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">find <span class="pl-c1">.</span> -name <span class="pl-s"><span class="pl-pds">'</span>*.pdf<span class="pl-pds">'</span></span> -exec pdftotext {} <span class="pl-cce">\;</span></td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-gistfile1-sh-LC5" class="blob-code blob-code-inner js-file-line">cat <span class="pl-k">*</span>.txt<span class="pl-k">&gt;</span>../nplggovgetext.txt</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L6" class="blob-num js-line-number" data-line-number="6"></td>
        <td id="file-gistfile1-sh-LC6" class="blob-code blob-code-inner js-file-line">rm <span class="pl-k">*</span>.pdf <span class="pl-k">*</span>.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232918/raw/73d2fd90e946986bc95dc4a0a8d470498b3afd4d/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232918#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>ვიწერთ forum.ge-ს</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232921.js"></script><link rel="stylesheet" href="/web/20150824145339/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232921" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> ../forumge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">scrapy crawl forum.ge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">mv forumgetext.txt ..</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232921/raw/904aebdb4ea478eaed4ca08eebbeb1737bb81d4e/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145339/https://gist.github.com/0xh3x/1232921#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145339/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>და lib.ge-ს</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232922.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232922" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> ../libge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">scrapy crawl lib.ge</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">mv libgetext.txt ..</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232922/raw/5361d42ac82ceaab36687812138935b263f0f4bc/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232922#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>გავაერთიანოთ ყველა ერთ ტექსტ ფაილში.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232923.js"></script><link rel="stylesheet" href="/web/20150824145342/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232923" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> ..</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">cat forumgetext.txt bukigetext.txt libgetext.txt nplggovgetext.txt wikitext.txt<span class="pl-k">&gt;</span>alltext.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232923/raw/3a0255ef607a63bfa29cf4af0f46f09ffe28f18e/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232923#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145342/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>დავაექსტრაქტოთ სიტყვები</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232925.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232925" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">python geotext2wordlist.py alltext.txt allwords.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232925/raw/9a8df6f22d31e78729a1c548d14880b03db4bb76/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232925#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>შევამოწმოთ ფაილების ზომები</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232927.js"></script><link rel="stylesheet" href="/web/20150824145343/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232927" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">ls -sh <span class="pl-k">*</span>.txt </td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">4.5G alltext.txt  3.8G allwords.txt   64M bukigetext.txt  118M forumgetext.txt  251M libgetext.txt  778M nplggovgetext.txt  379M wikitext.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232927/raw/3074d37776f934b4207bff59fdf0ff2d1e7e2ae1/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232927#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145343/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>შედეგად მივიღეთ 4.5GB ტექსტი&nbsp;<br>დავითვალოთ სიტყვების რაოდენობა allwords.txt-ში</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232928.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232928" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">wc allwords.txt </td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line"> 209783071  209783071 4078830739 allwords.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232928/raw/3d25cacb106e802e36bb9d9516482b8d78bdc8ab/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232928#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>209,783,071 სიტყვა!</p>
<p>&nbsp;</p>
<p><span style="font-size: medium;">მონაცემების დამუშავება</span></p>
<p>მონაცემების დასამუშავებლად გამოვიყენებ Hadoop-ს რომელიც 31 node-სგან შესდგება.</p>
<p></p><div class="posterousGalleryMainDiv p_embed p_image_embed" data-posterous-file-list="%5B%7B%22large%22%3A%22http%3A%2F%2Fgetfile6.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FndqaxigkCFxbEjupwvrmBilbrAbhjkktIxFdCodHiAsBhvmzwGIllkDjDmdF%2Fj12Cr7wBjGWaB.png.scaled1000.png%22%2C%22originalWidth%22%3A%22986%22%2C%22largeWidth%22%3A%22986%22%2C%22thumb%22%3A%22http%3A%2F%2Fgetfile3.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FndqaxigkCFxbEjupwvrmBilbrAbhjkktIxFdCodHiAsBhvmzwGIllkDjDmdF%2Fj12Cr7wBjGWaB.png.thumb.png%22%2C%22originalHeight%22%3A%22118%22%2C%22largeHeight%22%3A%22118%22%2C%22thumbWidth%22%3A%2236%22%2C%22height%22%3A%2271%22%2C%22main%22%3A%22http%3A%2F%2Fgetfile7.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FndqaxigkCFxbEjupwvrmBilbrAbhjkktIxFdCodHiAsBhvmzwGIllkDjDmdF%2Fj12Cr7wBjGWaB.png.scaled595.png%22%2C%22thumbHeight%22%3A%2236%22%2C%22originalSize%22%3A%2218%22%2C%22original%22%3A%22http%3A%2F%2Fgetfile6.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FndqaxigkCFxbEjupwvrmBilbrAbhjkktIxFdCodHiAsBhvmzwGIllkDjDmdF%2Fj12Cr7wBjGWaB.png%22%2C%22width%22%3A%22595%22%7D%5D" data-posterous-image-gallery-initialized="true" data-posterous-image-gallery="true" data-posterous-options="%7B%22zipFile%22%3Anull%2C%22zipFileSize%22%3Anull%2C%22external_url%22%3Anull%2C%22showDownload%22%3Atrue%2C%22url_slug%22%3A%2271533514%22%7D"><a href="#" onclick="return false;" class="posterousGalleryMainlink"><img src="http://getfile7.posterous.com/getfile/files.posterous.com/temp-2011-09-21/ndqaxigkCFxbEjupwvrmBilbrAbhjkktIxFdCodHiAsBhvmzwGIllkDjDmdF/j12Cr7wBjGWaB.png.scaled595.png" width="595" height="71" id="mainImage"><span class="show" id=""><div style="font-size:14px;position:absolute;right:10px;bottom:0px;" id="-dl3"><a href="#" onclick="return false" class="view_slideshow" data-posterous-tooltip="Click to view in full screen"></a></div><div style="font-size: 14px; display: none;" id="-dl2" class="posterousGalleryLink">Download this gallery (ZIP, null KB)</div><div style="font-size: 14px;" id="-dl1" class="posterousGalleryLink">Download full size (18 KB)</div></span></a></div>
<p></p>
<p>დავზიპოთ allwords.txt, ავთვირთოთ სერვერზე, განვზიპოთ სერვერზე ატვირთულო ფაილი და ავტვირთოთ Hadoop-ის DFS-ში</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232932.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232932" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">gzip allwords.txt</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">scp allwords.gz user@hadoopserver:/path/to/dir/kadata</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">ssh user@hadoopserver</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> /path/to/dir/kadata</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-gistfile1-sh-LC5" class="blob-code blob-code-inner js-file-line">gunzip allwords.gz</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L6" class="blob-num js-line-number" data-line-number="6"></td>
        <td id="file-gistfile1-sh-LC6" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> /Hadoop</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L7" class="blob-num js-line-number" data-line-number="7"></td>
        <td id="file-gistfile1-sh-LC7" class="blob-code blob-code-inner js-file-line">bin/hadoop dfs -copyFromLocal /path/to/dir/kadata /user/kadata</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232932/raw/8e0a6ca6220746f8c015a1b4c362678df3bef77f/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232932#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>პირველ რიგში დავითვალოთ ყველაზე ხშირად გამოყენებადი სიტყვები. ეს ძალიან მარტივად კეთდება Hadoop-ის MapReduce სისტემაში, მეტიც wordcount "Hello World" ამოცანად ითვლება.</p>
<p>Hadoop-ს მოყვება მაგალითები რომელიც მოთავსებულია hadoop-0.20.2-examples.jar (სადაც 0.20.2 hadoop-ის ვერსიაა) ფაილში. სიტყვების დათვლა ერთერთია ამ მაგალითებში.</p>
<p>&nbsp;</p>
<p>wordcount-ს აქვს 2 პარამეტრი input და output დირექტორიები</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232935.js"></script><link rel="stylesheet" href="/web/20150824145343/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232935" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">bin/hadoop jar hadoop-0.20.2-examples.jar wordcount /user/kadata /user/kadata-output</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232935/raw/384958b6a160f85cdf7712278585c671ce92a1c9/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232935#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145343/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>მთლიანი ფაილის დამუშავებას 2წუთი და 20წამი მოანდომა<br>შედეგად მივიღეთ ტექსტური ფაილი შემდეგი ფორმატით</p>
<p>სიტყვა n</p>
<p>...</p>
<p>სადაც n არის სიტყვის რაოდენობა. სიტყვები ანბანურადაა დალაგებული.<br>გადმოვიწეროთ შედეგი DFS-დან ლოკალურ ფაილურ სისტემაზე, შევამოწმოთ ზომა და სიტყვების რაოდენობა</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232938.js"></script><link rel="stylesheet" href="/web/20150824145342/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232938" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">bin/hadoop dfs -getmerge /user/kadata-output /path/to/dir/kadata</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> /path/to/dir/kadata</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">ls -sh kadata-output </td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">159M kadata-output</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-gistfile1-sh-LC5" class="blob-code blob-code-inner js-file-line">wc -l kadata-output </td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L6" class="blob-num js-line-number" data-line-number="6"></td>
        <td id="file-gistfile1-sh-LC6" class="blob-code blob-code-inner js-file-line">4839699 kadata-output</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232938/raw/95c2c447232ac946d7cc4da778443ba8463d55cc/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232938#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145342/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>მივიღეთ 4,839,699 უნიკალური სიტყვა.</p>
<p>სიტყვების რეიტინგის მიხედვით დასალაგებლად გამოვიყენებ Pig-ს. PigLatin არის Pig-ის DSL რომელიც აადვილებს MapReduce ამოცანების წერას Hadoop-ზე.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232942.js"></script><link rel="stylesheet" href="/web/20150824145343/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232942" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line">pig</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">grunt<span class="pl-k">&gt;</span> raw = LOAD <span class="pl-s"><span class="pl-pds">'</span>/user/kadata-output/part-r-00000<span class="pl-pds">'</span></span> USING PigStorage(<span class="pl-s"><span class="pl-pds">'</span>\t<span class="pl-pds">'</span></span>) AS (word:chararray, cnt:int)<span class="pl-k">;</span></td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">grunt<span class="pl-k">&gt;</span> raw_ordered = ORDER raw BY cnt DESC, word<span class="pl-k">;</span></td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">grunt<span class="pl-k">&gt;</span> STORE raw_ordered INTO <span class="pl-s"><span class="pl-pds">'</span>/user/kadata-output-sorted<span class="pl-pds">'</span></span> USING <span class="pl-en">PigStorage</span>();</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232942/raw/3ae3876b29af45dde664d0b1cd1af92a6105ce3d/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145343/https://gist.github.com/0xh3x/1232942#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145343/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>სორტირებას მოანდომა 3 წუთი და 11 წამი<br>გადმოვიწეროთ DFS-ის /user/kadata-output-sorted დირექტორიიდან დასორტირებული ფაილი</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232943.js"></script><link rel="stylesheet" href="/web/20150824145342/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232943" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> /Hadoop</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">bin/hadoop dfs -getmerge /user/kadata-output-sorted /path/to/dir/kadata/allwords-unique-sorted.txt</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232943/raw/266c44e7b558e7bce8d7987118989eabce512f6e/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145342/https://gist.github.com/0xh3x/1232943#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145342/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>ვნახოთ 100 ყველაზე პოპულარული სიტყვა და მათი რეიტინგი.</p>
<p><script src="/web/20130524144932js_/https://gist.github.com/1232945.js"></script><link rel="stylesheet" href="/web/20150824145341/https://assets-cdn.github.com/assets/gist/embed-da83046148bad9b15646a63deaa158bb4d2a95b81ed18adc1f387871fcfcf2f4.css"></p><div id="gist1232945" class="gist">
    <div class="gist-file">
      <div class="gist-data">
        <div class="js-gist-file-update-container js-task-list-container file-box">
  <div id="file-gistfile1-sh" class="file">
    

  <div class="blob-wrapper data type-shell">
      <table class="highlight tab-size js-file-line-container" data-tab-size="8">
      <tbody><tr>
        <td id="file-gistfile1-sh-L1" class="blob-num js-line-number" data-line-number="1"></td>
        <td id="file-gistfile1-sh-LC1" class="blob-code blob-code-inner js-file-line"><span class="pl-c1">cd</span> /path/to/dir/kadata</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L2" class="blob-num js-line-number" data-line-number="2"></td>
        <td id="file-gistfile1-sh-LC2" class="blob-code blob-code-inner js-file-line">head -100 allwords-unique-sorted.txt</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L3" class="blob-num js-line-number" data-line-number="3"></td>
        <td id="file-gistfile1-sh-LC3" class="blob-code blob-code-inner js-file-line">
</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L4" class="blob-num js-line-number" data-line-number="4"></td>
        <td id="file-gistfile1-sh-LC4" class="blob-code blob-code-inner js-file-line">და	8670483</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L5" class="blob-num js-line-number" data-line-number="5"></td>
        <td id="file-gistfile1-sh-LC5" class="blob-code blob-code-inner js-file-line">არ	3767689</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L6" class="blob-num js-line-number" data-line-number="6"></td>
        <td id="file-gistfile1-sh-LC6" class="blob-code blob-code-inner js-file-line">რომ	2586399</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L7" class="blob-num js-line-number" data-line-number="7"></td>
        <td id="file-gistfile1-sh-LC7" class="blob-code blob-code-inner js-file-line">რა	1869882</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L8" class="blob-num js-line-number" data-line-number="8"></td>
        <td id="file-gistfile1-sh-LC8" class="blob-code blob-code-inner js-file-line">თუ	1735775</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L9" class="blob-num js-line-number" data-line-number="9"></td>
        <td id="file-gistfile1-sh-LC9" class="blob-code blob-code-inner js-file-line">ეს	1428843</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L10" class="blob-num js-line-number" data-line-number="10"></td>
        <td id="file-gistfile1-sh-LC10" class="blob-code blob-code-inner js-file-line">უნდა	1240086</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L11" class="blob-num js-line-number" data-line-number="11"></td>
        <td id="file-gistfile1-sh-LC11" class="blob-code blob-code-inner js-file-line">მე	1191923</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L12" class="blob-num js-line-number" data-line-number="12"></td>
        <td id="file-gistfile1-sh-LC12" class="blob-code blob-code-inner js-file-line">ამ	1133752</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L13" class="blob-num js-line-number" data-line-number="13"></td>
        <td id="file-gistfile1-sh-LC13" class="blob-code blob-code-inner js-file-line">მაგრამ	987038</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L14" class="blob-num js-line-number" data-line-number="14"></td>
        <td id="file-gistfile1-sh-LC14" class="blob-code blob-code-inner js-file-line">არის	958995</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L15" class="blob-num js-line-number" data-line-number="15"></td>
        <td id="file-gistfile1-sh-LC15" class="blob-code blob-code-inner js-file-line">კი	918938</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L16" class="blob-num js-line-number" data-line-number="16"></td>
        <td id="file-gistfile1-sh-LC16" class="blob-code blob-code-inner js-file-line">არა	907085</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L17" class="blob-num js-line-number" data-line-number="17"></td>
        <td id="file-gistfile1-sh-LC17" class="blob-code blob-code-inner js-file-line">იყო	814109</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L18" class="blob-num js-line-number" data-line-number="18"></td>
        <td id="file-gistfile1-sh-LC18" class="blob-code blob-code-inner js-file-line">ვერ	761302</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L19" class="blob-num js-line-number" data-line-number="19"></td>
        <td id="file-gistfile1-sh-LC19" class="blob-code blob-code-inner js-file-line">ის	757457</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L20" class="blob-num js-line-number" data-line-number="20"></td>
        <td id="file-gistfile1-sh-LC20" class="blob-code blob-code-inner js-file-line">ან	653509</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L21" class="blob-num js-line-number" data-line-number="21"></td>
        <td id="file-gistfile1-sh-LC21" class="blob-code blob-code-inner js-file-line">ეგ	620925</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L22" class="blob-num js-line-number" data-line-number="22"></td>
        <td id="file-gistfile1-sh-LC22" class="blob-code blob-code-inner js-file-line">რო	605240</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L23" class="blob-num js-line-number" data-line-number="23"></td>
        <td id="file-gistfile1-sh-LC23" class="blob-code blob-code-inner js-file-line">ერთი	589008</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L24" class="blob-num js-line-number" data-line-number="24"></td>
        <td id="file-gistfile1-sh-LC24" class="blob-code blob-code-inner js-file-line">ს	560012</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L25" class="blob-num js-line-number" data-line-number="25"></td>
        <td id="file-gistfile1-sh-LC25" class="blob-code blob-code-inner js-file-line">რაც	539270</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L26" class="blob-num js-line-number" data-line-number="26"></td>
        <td id="file-gistfile1-sh-LC26" class="blob-code blob-code-inner js-file-line">მერე	538679</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L27" class="blob-num js-line-number" data-line-number="27"></td>
        <td id="file-gistfile1-sh-LC27" class="blob-code blob-code-inner js-file-line">ისე	527125</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L28" class="blob-num js-line-number" data-line-number="28"></td>
        <td id="file-gistfile1-sh-LC28" class="blob-code blob-code-inner js-file-line">შენ	478623</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L29" class="blob-num js-line-number" data-line-number="29"></td>
        <td id="file-gistfile1-sh-LC29" class="blob-code blob-code-inner js-file-line">როგორც	458847</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L30" class="blob-num js-line-number" data-line-number="30"></td>
        <td id="file-gistfile1-sh-LC30" class="blob-code blob-code-inner js-file-line">აქვს	457638</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L31" class="blob-num js-line-number" data-line-number="31"></td>
        <td id="file-gistfile1-sh-LC31" class="blob-code blob-code-inner js-file-line">აქ	429748</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L32" class="blob-num js-line-number" data-line-number="32"></td>
        <td id="file-gistfile1-sh-LC32" class="blob-code blob-code-inner js-file-line">ძალიან	424854</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L33" class="blob-num js-line-number" data-line-number="33"></td>
        <td id="file-gistfile1-sh-LC33" class="blob-code blob-code-inner js-file-line">სხვა	422943</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L34" class="blob-num js-line-number" data-line-number="34"></td>
        <td id="file-gistfile1-sh-LC34" class="blob-code blob-code-inner js-file-line">ჩემი	421896</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L35" class="blob-num js-line-number" data-line-number="35"></td>
        <td id="file-gistfile1-sh-LC35" class="blob-code blob-code-inner js-file-line">უფრო	417085</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L36" class="blob-num js-line-number" data-line-number="36"></td>
        <td id="file-gistfile1-sh-LC36" class="blob-code blob-code-inner js-file-line">არც	402073</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L37" class="blob-num js-line-number" data-line-number="37"></td>
        <td id="file-gistfile1-sh-LC37" class="blob-code blob-code-inner js-file-line">მაინც	399627</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L38" class="blob-num js-line-number" data-line-number="38"></td>
        <td id="file-gistfile1-sh-LC38" class="blob-code blob-code-inner js-file-line">დიდი	384253</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L39" class="blob-num js-line-number" data-line-number="39"></td>
        <td id="file-gistfile1-sh-LC39" class="blob-code blob-code-inner js-file-line">შეიძლება	383449</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L40" class="blob-num js-line-number" data-line-number="40"></td>
        <td id="file-gistfile1-sh-LC40" class="blob-code blob-code-inner js-file-line">ხო	372817</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L41" class="blob-num js-line-number" data-line-number="41"></td>
        <td id="file-gistfile1-sh-LC41" class="blob-code blob-code-inner js-file-line">იქნება	371651</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L42" class="blob-num js-line-number" data-line-number="42"></td>
        <td id="file-gistfile1-sh-LC42" class="blob-code blob-code-inner js-file-line">როგორ	359903</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L43" class="blob-num js-line-number" data-line-number="43"></td>
        <td id="file-gistfile1-sh-LC43" class="blob-code blob-code-inner js-file-line">ასე	359476</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L44" class="blob-num js-line-number" data-line-number="44"></td>
        <td id="file-gistfile1-sh-LC44" class="blob-code blob-code-inner js-file-line">ყველა	353031</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L45" class="blob-num js-line-number" data-line-number="45"></td>
        <td id="file-gistfile1-sh-LC45" class="blob-code blob-code-inner js-file-line">უკვე	339616</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L46" class="blob-num js-line-number" data-line-number="46"></td>
        <td id="file-gistfile1-sh-LC46" class="blob-code blob-code-inner js-file-line">ვიცი	337805</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L47" class="blob-num js-line-number" data-line-number="47"></td>
        <td id="file-gistfile1-sh-LC47" class="blob-code blob-code-inner js-file-line">იმ	334887</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L48" class="blob-num js-line-number" data-line-number="48"></td>
        <td id="file-gistfile1-sh-LC48" class="blob-code blob-code-inner js-file-line">რომელიც	332988</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L49" class="blob-num js-line-number" data-line-number="49"></td>
        <td id="file-gistfile1-sh-LC49" class="blob-code blob-code-inner js-file-line">კიდევ	332425</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L50" class="blob-num js-line-number" data-line-number="50"></td>
        <td id="file-gistfile1-sh-LC50" class="blob-code blob-code-inner js-file-line">ვარ	318228</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L51" class="blob-num js-line-number" data-line-number="51"></td>
        <td id="file-gistfile1-sh-LC51" class="blob-code blob-code-inner js-file-line">აი	318082</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L52" class="blob-num js-line-number" data-line-number="52"></td>
        <td id="file-gistfile1-sh-LC52" class="blob-code blob-code-inner js-file-line">იყოს	312963</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L53" class="blob-num js-line-number" data-line-number="53"></td>
        <td id="file-gistfile1-sh-LC53" class="blob-code blob-code-inner js-file-line">ნუ	299198</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L54" class="blob-num js-line-number" data-line-number="54"></td>
        <td id="file-gistfile1-sh-LC54" class="blob-code blob-code-inner js-file-line">ეხლა	296293</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L55" class="blob-num js-line-number" data-line-number="55"></td>
        <td id="file-gistfile1-sh-LC55" class="blob-code blob-code-inner js-file-line">მისი	293569</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L56" class="blob-num js-line-number" data-line-number="56"></td>
        <td id="file-gistfile1-sh-LC56" class="blob-code blob-code-inner js-file-line">ხომ	282707</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L57" class="blob-num js-line-number" data-line-number="57"></td>
        <td id="file-gistfile1-sh-LC57" class="blob-code blob-code-inner js-file-line">მაგ	282264</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L58" class="blob-num js-line-number" data-line-number="58"></td>
        <td id="file-gistfile1-sh-LC58" class="blob-code blob-code-inner js-file-line">ჯერ	281404</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L59" class="blob-num js-line-number" data-line-number="59"></td>
        <td id="file-gistfile1-sh-LC59" class="blob-code blob-code-inner js-file-line">რამე	279240</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L60" class="blob-num js-line-number" data-line-number="60"></td>
        <td id="file-gistfile1-sh-LC60" class="blob-code blob-code-inner js-file-line">რას	277107</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L61" class="blob-num js-line-number" data-line-number="61"></td>
        <td id="file-gistfile1-sh-LC61" class="blob-code blob-code-inner js-file-line">აბა	276167</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L62" class="blob-num js-line-number" data-line-number="62"></td>
        <td id="file-gistfile1-sh-LC62" class="blob-code blob-code-inner js-file-line">მინდა	275499</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L63" class="blob-num js-line-number" data-line-number="63"></td>
        <td id="file-gistfile1-sh-LC63" class="blob-code blob-code-inner js-file-line">მხოლოდ	275431</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L64" class="blob-num js-line-number" data-line-number="64"></td>
        <td id="file-gistfile1-sh-LC64" class="blob-code blob-code-inner js-file-line">ანუ	271518</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L65" class="blob-num js-line-number" data-line-number="65"></td>
        <td id="file-gistfile1-sh-LC65" class="blob-code blob-code-inner js-file-line">მარა	270009</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L66" class="blob-num js-line-number" data-line-number="66"></td>
        <td id="file-gistfile1-sh-LC66" class="blob-code blob-code-inner js-file-line">მაშინ	269330</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L67" class="blob-num js-line-number" data-line-number="67"></td>
        <td id="file-gistfile1-sh-LC67" class="blob-code blob-code-inner js-file-line">შემდეგ	267858</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L68" class="blob-num js-line-number" data-line-number="68"></td>
        <td id="file-gistfile1-sh-LC68" class="blob-code blob-code-inner js-file-line">მაქვს	263872</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L69" class="blob-num js-line-number" data-line-number="69"></td>
        <td id="file-gistfile1-sh-LC69" class="blob-code blob-code-inner js-file-line">ა	259570</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L70" class="blob-num js-line-number" data-line-number="70"></td>
        <td id="file-gistfile1-sh-LC70" class="blob-code blob-code-inner js-file-line">სულ	259319</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L71" class="blob-num js-line-number" data-line-number="71"></td>
        <td id="file-gistfile1-sh-LC71" class="blob-code blob-code-inner js-file-line">ერთ	256903</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L72" class="blob-num js-line-number" data-line-number="72"></td>
        <td id="file-gistfile1-sh-LC72" class="blob-code blob-code-inner js-file-line">კარგი	254748</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L73" class="blob-num js-line-number" data-line-number="73"></td>
        <td id="file-gistfile1-sh-LC73" class="blob-code blob-code-inner js-file-line">მეც	252669</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L74" class="blob-num js-line-number" data-line-number="74"></td>
        <td id="file-gistfile1-sh-LC74" class="blob-code blob-code-inner js-file-line">წლის	246383</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L75" class="blob-num js-line-number" data-line-number="75"></td>
        <td id="file-gistfile1-sh-LC75" class="blob-code blob-code-inner js-file-line">ხარ	245009</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L76" class="blob-num js-line-number" data-line-number="76"></td>
        <td id="file-gistfile1-sh-LC76" class="blob-code blob-code-inner js-file-line">საქართველოს	238956</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L77" class="blob-num js-line-number" data-line-number="77"></td>
        <td id="file-gistfile1-sh-LC77" class="blob-code blob-code-inner js-file-line">დროს	236144</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L78" class="blob-num js-line-number" data-line-number="78"></td>
        <td id="file-gistfile1-sh-LC78" class="blob-code blob-code-inner js-file-line">როცა	234250</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L79" class="blob-num js-line-number" data-line-number="79"></td>
        <td id="file-gistfile1-sh-LC79" class="blob-code blob-code-inner js-file-line">ახლა	231746</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L80" class="blob-num js-line-number" data-line-number="80"></td>
        <td id="file-gistfile1-sh-LC80" class="blob-code blob-code-inner js-file-line">არაა	226320</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L81" class="blob-num js-line-number" data-line-number="81"></td>
        <td id="file-gistfile1-sh-LC81" class="blob-code blob-code-inner js-file-line">მაგარი	225102</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L82" class="blob-num js-line-number" data-line-number="82"></td>
        <td id="file-gistfile1-sh-LC82" class="blob-code blob-code-inner js-file-line">რაღაც	224439</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L83" class="blob-num js-line-number" data-line-number="83"></td>
        <td id="file-gistfile1-sh-LC83" class="blob-code blob-code-inner js-file-line">კაი	220666</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L84" class="blob-num js-line-number" data-line-number="84"></td>
        <td id="file-gistfile1-sh-LC84" class="blob-code blob-code-inner js-file-line">ახალი	220226</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L85" class="blob-num js-line-number" data-line-number="85"></td>
        <td id="file-gistfile1-sh-LC85" class="blob-code blob-code-inner js-file-line">თან	213358</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L86" class="blob-num js-line-number" data-line-number="86"></td>
        <td id="file-gistfile1-sh-LC86" class="blob-code blob-code-inner js-file-line">ჩვენ	212324</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L87" class="blob-num js-line-number" data-line-number="87"></td>
        <td id="file-gistfile1-sh-LC87" class="blob-code blob-code-inner js-file-line">გინდა	210186</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L88" class="blob-num js-line-number" data-line-number="88"></td>
        <td id="file-gistfile1-sh-LC88" class="blob-code blob-code-inner js-file-line">აღარ	210044</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L89" class="blob-num js-line-number" data-line-number="89"></td>
        <td id="file-gistfile1-sh-LC89" class="blob-code blob-code-inner js-file-line">კიდე	207336</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L90" class="blob-num js-line-number" data-line-number="90"></td>
        <td id="file-gistfile1-sh-LC90" class="blob-code blob-code-inner js-file-line">თავის	206154</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L91" class="blob-num js-line-number" data-line-number="91"></td>
        <td id="file-gistfile1-sh-LC91" class="blob-code blob-code-inner js-file-line">შენი	205685</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L92" class="blob-num js-line-number" data-line-number="92"></td>
        <td id="file-gistfile1-sh-LC92" class="blob-code blob-code-inner js-file-line">დღეს	205098</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L93" class="blob-num js-line-number" data-line-number="93"></td>
        <td id="file-gistfile1-sh-LC93" class="blob-code blob-code-inner js-file-line">ყველაფერი	204904</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L94" class="blob-num js-line-number" data-line-number="94"></td>
        <td id="file-gistfile1-sh-LC94" class="blob-code blob-code-inner js-file-line">გილოცავ	204619</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L95" class="blob-num js-line-number" data-line-number="95"></td>
        <td id="file-gistfile1-sh-LC95" class="blob-code blob-code-inner js-file-line">ალბათ	202098</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L96" class="blob-num js-line-number" data-line-number="96"></td>
        <td id="file-gistfile1-sh-LC96" class="blob-code blob-code-inner js-file-line">ში	198842</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L97" class="blob-num js-line-number" data-line-number="97"></td>
        <td id="file-gistfile1-sh-LC97" class="blob-code blob-code-inner js-file-line">ამას	196630</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L98" class="blob-num js-line-number" data-line-number="98"></td>
        <td id="file-gistfile1-sh-LC98" class="blob-code blob-code-inner js-file-line">მარტო	194098</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L99" class="blob-num js-line-number" data-line-number="99"></td>
        <td id="file-gistfile1-sh-LC99" class="blob-code blob-code-inner js-file-line">ყველაზე	193261</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L100" class="blob-num js-line-number" data-line-number="100"></td>
        <td id="file-gistfile1-sh-LC100" class="blob-code blob-code-inner js-file-line">მეორე	191083</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L101" class="blob-num js-line-number" data-line-number="101"></td>
        <td id="file-gistfile1-sh-LC101" class="blob-code blob-code-inner js-file-line">ასეთი	191066</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L102" class="blob-num js-line-number" data-line-number="102"></td>
        <td id="file-gistfile1-sh-LC102" class="blob-code blob-code-inner js-file-line">სად	191057</td>
      </tr>
      <tr>
        <td id="file-gistfile1-sh-L103" class="blob-num js-line-number" data-line-number="103"></td>
        <td id="file-gistfile1-sh-LC103" class="blob-code blob-code-inner js-file-line">ზე	190618</td>
      </tr>
</tbody></table>

  </div>

  </div>
  
</div>

      </div>
      <div class="gist-meta">
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232945/raw/c0e2347ceb43a344f1f9f5ea48c7adeb71e40251/gistfile1.sh" style="float:right">view raw</a>
        <a href="/web/20150824145341/https://gist.github.com/0xh3x/1232945#file-gistfile1-sh">gistfile1.sh</a>
        hosted with ❤ by <a href="/web/20150824145341/https://github.com">GitHub</a>
      </div>
    </div>
</div>
<p></p>
<p>ესეც wordcloud :)</p>
<p></p><div class="posterousGalleryMainDiv p_embed p_image_embed" data-posterous-file-list="%5B%7B%22large%22%3A%22http%3A%2F%2Fgetfile6.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FGaokAeHAGftvHzafqJgobwgsvbxyuGjuprFCeqxntDvcGIygtJafGBuxIBwI%2Ftagcloud.png.scaled1000.png%22%2C%22originalWidth%22%3A%22835%22%2C%22largeWidth%22%3A%22835%22%2C%22thumb%22%3A%22http%3A%2F%2Fgetfile1.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FGaokAeHAGftvHzafqJgobwgsvbxyuGjuprFCeqxntDvcGIygtJafGBuxIBwI%2Ftagcloud.png.thumb.png%22%2C%22originalHeight%22%3A%22540%22%2C%22largeHeight%22%3A%22540%22%2C%22thumbWidth%22%3A%2236%22%2C%22height%22%3A%22385%22%2C%22main%22%3A%22http%3A%2F%2Fgetfile9.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FGaokAeHAGftvHzafqJgobwgsvbxyuGjuprFCeqxntDvcGIygtJafGBuxIBwI%2Ftagcloud.png.scaled595.png%22%2C%22thumbHeight%22%3A%2236%22%2C%22originalSize%22%3A%22156%22%2C%22original%22%3A%22http%3A%2F%2Fgetfile4.posterous.com%2Fgetfile%2Ffiles.posterous.com%2Ftemp-2011-09-21%2FGaokAeHAGftvHzafqJgobwgsvbxyuGjuprFCeqxntDvcGIygtJafGBuxIBwI%2Ftagcloud.png%22%2C%22width%22%3A%22595%22%7D%5D" data-posterous-image-gallery-initialized="true" data-posterous-image-gallery="true" data-posterous-options="%7B%22zipFile%22%3Anull%2C%22zipFileSize%22%3Anull%2C%22external_url%22%3Anull%2C%22showDownload%22%3Atrue%2C%22url_slug%22%3A%2271533514%22%7D"><a href="#" onclick="return false;" class="posterousGalleryMainlink"><img src="http://getfile9.posterous.com/getfile/files.posterous.com/temp-2011-09-21/GaokAeHAGftvHzafqJgobwgsvbxyuGjuprFCeqxntDvcGIygtJafGBuxIBwI/tagcloud.png.scaled595.png" width="595" height="385" id="mainImage"><span class="show" id=""><div style="font-size:14px;position:absolute;right:10px;bottom:0px;" id="-dl3"><a href="#" onclick="return false" class="view_slideshow" data-posterous-tooltip="Click to view in full screen"></a></div><div style="font-size: 14px; display: none;" id="-dl2" class="posterousGalleryLink">Download this gallery (ZIP, null KB)</div><div style="font-size: 14px;" id="-dl1" class="posterousGalleryLink">Download full size (156 KB)</div></span></a></div>
<p></p>
<p>&nbsp;</p>
<p>ამ ფაილის გადმოწერა შეგიძლიათ ამ ბმულიდან <a href="/web/20130524144932/http://min.us/lIRqseClqFtT4">http://min.us/lIRqseClqFtT4</a><br>შემდეგ პოსტებში შევეცდები სხვადასხვა ანალიზი გავუკეთო ამ მონაცემებს მაგალითად:<br>ასოების რეიტინგი, ხმოვანთა და თანხმოვანთა თანაფარდობათა რეიტინგი, სიტყვის პირველი და ბოლო ასოების რეიტინგი, სიტყვის სიგრძეების რეიტინგი.<br>ასევე საინტერესო იქნება ngram-ების დაგენერირება. მარა ეს ყველაფერი მომავლისთვის.</p>

                
              </article>
            
          </div>
