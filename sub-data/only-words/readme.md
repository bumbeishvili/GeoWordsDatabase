Folder contains only unique english encoded words in .csv format

This data was extracted with the folowing command 

        SELECT w.Id,
               w.word_eng 
        FROM geowords.words w
        inner join
         (select distinct word_id 
          from words_history 
          where source_id != 37) not_lastnames
        on w.id = not_lastnames.word_id
        INTO OUTFILE 'd://all_words_except_unique_source_lastname.csv'
        FIELDS TERMINATED BY ','
