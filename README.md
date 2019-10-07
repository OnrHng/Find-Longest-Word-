# Find-Longest-Word-
how can you find the longest word in the string

the function LongestWord(sen) take the sen parameter being passed and return the largest word in the string. If there are two or more words that are the same length, return the first word from the string with that length. Ignore punctuation....

      function LongestWord(sen) {

        let result = '' ;
         const word = sen.replace(/[^a-zA-Zsd]/g, ' ').split(' ').map ( word => word.length > result.length ? result = word : null ); 
        return result;
      }
      LongestWord('This% is a beautiful sentence100#')
best
