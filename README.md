<!DOCTYPE html>
<html lang="en">
<head>
    <title> HTML </title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
.table-hover tbody tr:hover td{
           background-color:F8F8F8;
          color:grey;
}

   table, th, td {
            border: 0px solid grey;
            box-shadow: 0px 0px 0px #888888;
             
        }
        th, td {
            padding: 50px;
            spacing:20px;
            box-shadow: 0px 0px 0px #888888;

        }
#row1 {
           background-color:F8F8F8;
           font-family: "Times New Roman", Times, serif;
            
           
           }
#row2{
           background-color:#F0F0F0;
           font-family: "Times New Roman", Times, serif;
           
           }
#row3{
           background-color:#f0f0f0;
           font-family: "Times New Roman", Times, serif;
           
           }
.n1 th:hover {
  background-color: SteelBlue;
  color: black;
}
#row4{
           background-color:F8F8F8;
           font-family: "Times New Roman", Times, serif;
           }
#row5{
           background-color:F8F8F8;
           font-family: "Times New Roman", Times, serif;
           }
#col{
           text-align:center;
           }
n1{
           text-align:center;
           }
#n2{
           text-align:left;
          

           }


m1{
           
           text-align:center;
          

           }


    </style>
</head>
<body>
   
    <table style="border: medium solid #FFFFFF; position:fixes;" border="3" width="100%";>
        <tr id="row1">
            <th class="pic1" id="pic1"><img src="wifi.jpg" alt="wifi" width="30" height="30"></th>
<th ></th>
            
        </tr>
        <tr id="row2">
            <th><img src="school.jpg" alt="school" width="30" height="30"><br><h5> Student</h5></th>
            <td><img src="video.jpg" alt="video" width="12" height="12">  videos</td>
        </tr>
          <tr class="n1">
            <th><img src="book.jpg" alt="book" width="30" height="30"> <br><h5><b>Lesson plan</b></h5></th><br><br>
          <td id="m1"><label> <textarea rows="2" cols="100" name=comment form="useform" placeholder="Insert URL here"/></textarea> </label><br><br><b><center>or</center></b><br><br></td>
</tr>

        <tr>
            <th><img src="s1.jpg" alt="settings" width="30" height="30"><br><h5>Setting</h5></th>
         <th id="n2"><label><textarea rows="10" cols="20" name=comment form="useform" placeholder="Upload" ></textarea></label> </th> </tr>
            
        
    </table>
</body>
</html
