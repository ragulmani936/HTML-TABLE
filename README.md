# HTML-Table

## PROGRAM:

### index.html
~~~
<!DOCTYPE html>
<html>
    <head>
        <style>
            table,th,td{border:1px solid black}
        </style>

    </head>
<body>
    <table cellpadding ="5">
        <tr>
            <th align="center" colspan="4"><span style="background-color: yellow;">Day</span></th>

        </tr>
        <tr>
            <td>
                <ol type="1">
                    <li>wake up early</li>
                    <ul>
                        <li type="square">5AM</li><br>
                        <li>walk</li>
                        <li>jog</li>
                    </ul>
                </ol>
                
            </td>
            <td rowspan="3">

                <table width="100%">
                    <th align="center" colspan="2"><span style="background-color: yellow;">Things to watch</span></th>
                    <tr >
                        <td><img src="jog.jpg",width="100%"></td>
                        <td><img src="egg.jpg"width="100%"></td>

                    </tr>
                    <tr>
                        <td><img src="tea.jpg"width="100%"></td>
                        <td><img src="class.jpg"width="100%"></td>

                    </tr>

                </table>
            </td>


        </tr>
        <tr>
            <td><ol type="1" start="2">
                <li>breakfast</li> 
                <ul>
                    <li type="square">8AM</li>
<br></br>
                    <li>eggs</li>
                    <li>coffee</li>
                </ul>
            </ol></td>

        </tr>
        <tr>
            <td><ol type="1" start="3">
                <li>go to saveetha</li> 
                <ul>
                    <li type="square">8AM</li><br>
                    <li>attend class</li>
                    <li>to be continued</li>
                </ul>
            </ol></td>

        </tr>
    </table>
</body>
</html>
~~~

### OUTPUT:

![output](https://github.com/ragulmani936/HTML-Table/assets/94881918/f962cd20-ea42-40ca-bfe1-4dbf5769934d)
