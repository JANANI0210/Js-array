# CREATE A PROGRAM FOR NESTED ARRAY USIG JS

### AIM :
        To Create a program for Nested Array using JS Assignment.


Algorithm:
	
      Step 1: Start by creating a new folder. 
      Step 2: Create and Open the “index.html”, write the code.
      Step 3: Create a new CSS file “script.js” 
      Step 4: Declare a nested array variable to store the data.
      Step 5: Access the elements of the nested array using nested for loops.
      Step 6: Use the outer loop to iterate over the main array. Use the inner loop to iterate                        
                           over the sub-arrays within the main array.
      Step 7: Perform desired operations on the elements within the nested array. For                     
                           example, you can print them, calculate sums, or find specific values.
      Step 8: Use the console.log() function to display the results or perform further   
                 operations.

### PROGRAM :

index.html

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <link rel="stylesheet" href="assets/css/style.css">
          <title>Nested Array</title>
      </head>
      <body>

          <script src="assets/js/script.js"></script>
      </body>
      </html>


     script.js

      let array1 = [3,1]
      let array2 = [0,4]

      // IsNested(array1,array2)

      console.log(IsNested(array1,array2))

      function IsNested(array1,array2)
      {
          let min_value_array1 = 9999;
          let max_value_array1 = 0;
          let min_value_array2 = 9999;
          let max_value_array2 = 0;

              minValue = Infinity;
              maxValue = -Infinity;

              for (item of array1) {
                  // find minimum value
                  if (item < min_value_array1)
                      min_value_array1 = item;

                  // find maximum value
                  if (item > max_value_array1)
                      max_value_array1 = item;
              }

              for (item of array2) {
                  // find minimum value
                  if (item < min_value_array2)
                      min_value_array2 = item;

                  // find maximum value
                  if (item > max_value_array2)
                      max_value_array2 = item;
              }

              console.log(min_value_array1)
              console.log(max_value_array1)
              console.log(min_value_array2)
              console.log(max_value_array2)


          return (min_value_array1>min_value_array2)&&(max_value_array1<max_value_array2);

      }
 

### OUTPUT :

![image](https://github.com/JANANI0210/Js-array/assets/86832944/31583c54-a5d1-4baa-870d-bfc23354ad5c)


### RESULT :

      	Thus, the HTML & JS program to Create a program for Nested Array using JS was im[plemented successfully.




