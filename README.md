## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/maliat-hossain/maliat-hossain.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=HI, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1><head><title>Part 1</title></head>

        <body>
        
        <h1> Part 1 </h1>
        
        <script type="text/javascript">
            function changeBackground(color) {
    document.body.style.background = color;
}

window.addEventListener("load",function() { changeBackground('Aquamarine') });
        
        
        function reverseString(str) {
            
            var splitString = str.split(""); // var splitString = "hello".split("");
             
            
            var reverseArray = splitString.reverse(); // var reverseArray = ["h", "e", "l", "l", "o"].reverse();
             
           
            var joinArray = reverseArray.join(""); // var joinArray = ["o", "l", "l", "e", "h"].join("");
                
           
             return joinArray;
             
            }
        </script> 
        
        
        <script type="text/javascript">
        function perfrom_reverse(){
            var t = document.getElementById("target");
            t.innerHTML = reverseString(document.getElementById('reverse_string').value);
        }
        </script>
        
        <h2>(a) Reverse a String</h2>
        <p>
        <form>
            <input id="reverse_string" type="string" size="20">
            <input type="button" value="Reverse String" onClick="perfrom_reverse();">
        </form>
        </p>
        <div id="target"></div>
        
        
        <script type="text/javascript">
            function list_multiples(input_number){
               table_data = "<table>"
            
                for (var i = 1; i < 6; i++){
                 
                    var num1 = input_number * (4*i - 3);
                    var num2 = input_number * (4*i - 2);
                    var num3 = input_number * (4*i - 1);
                    var num4 = input_number * (4*i - 0);
        
                    row_data =    
                    '<tr>' + 
                    '<td>' + num1 + '</td>' + 
                    '<td>' + num2 + '</td>' + 
                    '<td>' + num3 + '</td>' + 
                    '<td>' + num4 + '</td>' + 
                    '</tr>'; 
                    table_data = table_data + row_data
                }
                table_data = table_data + "</table>"
            return table_data; 
            }
            </script>
        
        
        
        <script type="text/javascript">
            function perfrom_multiples(){
                var t = document.getElementById("target2");
                t.innerHTML = list_multiples(document.getElementById('number_input').value);
            }
        </script>
        
        
        <h2>(b) List first 20 multiples of number</h2>
        <p>
        <form>
            <input id="number_input" type="number" size="4">
            <input type="button" value="Number" onClick="perfrom_multiples();">
        </form>
        </p>
        <div id="target2"></div>
        
        </body>
        </html></h1>
</body>
</html>
