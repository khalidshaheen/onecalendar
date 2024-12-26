table.fixed {table-layout:fixed; width:90px;}/*Setting the table width is important!*/
table.fixed td {overflow:hidden;}/*Hide text outside the cell.*/
table.fixed td:nth-of-type(1) {width:20px;}/*Setting the width of column 1.*/
table.fixed td:nth-of-type(2) {width:30px;}/*Setting the width of column 2.*/
table.fixed td:nth-of-type(3) {width:40px;}/*Setting the width of column 3.*/

<table class fixed>
<tr><th></th><th></th></tr>
<tr><td>
Gregorian calendar 2025 <br>
Hijri calendar 1446

<table width="100%">
  <thead>
    <tr>
      <th width="50%">First header</th>
      <th width="50%">Second header long</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="50%"></td>
      <td width="50%"></td>
    </tr>
  </tbody>
</table>

</td><td style='text-align:center; vertical-align:middle'>

|Jan<br>يناير|May|Aug|Feb|Jun|Sep|Apr|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Oct|   |   |Mar|   |Dec|Jul|
|   |   |   |Nov|   |   |   |
|   |   |   |   |   |   |   |

</td></tr>

<tr><td>

|1|8|15|22|29|
|:-:|:-:|:-:|:-:|:-:|
|2|9|16|23|30|
|3|10|17|24|31|
|4|11|18|25|  |
|5|12|19|26|  |
|6|13|20|27|  |
|7|14|21|28|  |

</td><td>

|Wed|Thu|Fri|Sat|Sun|Mon|Tue|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Thu|Fri|Sat|Sun|Mon|Tue|Wed|
|Fri|Sat|Sun|Mon|Tue|Wed|Thu|
|Sat|Sun|Mon|Tue|Wed|Thu|Fri|
|Sun|Mon|Tue|Wed|Thu|Fri|Sat|
|Mon|Tue|Wed|Thu|Fri|Sat|Sun|
|Tue|Wed|Thu|Fri|Sat|Sun|Mon|


</td></tr> </table>
