# MombieStreet---Assessment-v2
2.1&amp;2.2

//2.1
<head>

</head>
<body>
    <script>
        for(let i = 1; i <= 100; i++){
    if(i % 3 == 0 && i % 5 == 0){
        console.log("FizzBuzz")
    }else if(i % 5 == 0){
        console.log("Buzz")
    }else if(i % 3 == 0){
        console.log("Fizz")
    }else{
        console.log(i)
    }     
}
    </script>
</body>
  
 
  
  
  
  
  
  //2.2
  <head>

</head>
<body>
    <script>
        let x = "# # # # "
let number = prompt("กรุณาใส่เลขที่ต้องการ")
for(let i = 1; i <= number; i++){
    console.log(i + " " + x)
}
    </script>
</body>
