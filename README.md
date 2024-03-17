# question_six
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <script language="javascript">
        /*Question 6: Count Vowels
    Write a program that counts the number of vowels in a sentence.
    eg " Hello World " => returns 2*/

    function word(){
      var y=prompt('enter a keyword');
      const z = 'aeiouAEIOU'; 
      let j =0;
      
      for(var i=0 ; i < y.length;i++){
        if(z.includes (y[i])){
          j++;
        }
      }
      document.write(j);
      return j;
    }
  </script>
</head>
<body>
  <button onclick="word()">return to letter</button>
</body>
</html>
