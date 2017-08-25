<!doctype html><html><head><title> ruuvi Beacon packet formats</title>
<style>code {size:160%;font-weight:bold;}    
td {vertical-align:top}
</style>


<body>
Ruuvi packet is embedded within 
<h2>
            <a href=https://github.com/google/eddystone/tree/master/eddystone-url 
>Eddystone URL</a></h2>
Frames in the Eddystone URL format are retrievable on many cellphones (including Android and iPhone ) via an installed widget.<br>
for example: <a href=           qqqq>&iquest;&iquest;     </a><P>
There are also applications which issue a notification whenever a new beacon is detected. <br>
for example: <a href=           qqqq>&iquest;&iquest;     </a><P>

Frame Specification <small>(summary)</small>:
<table border=1 cellspacing=0 cellpadding=2 style=border-style:solid>
<tr><td >&nbsp; byte<br>
&nbsp;offset &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<td>&nbsp;range of<br> values    <td>
<tr><td>&nbsp;0    <td> &nbsp;   x10 <td>  &nbsp;   Frame Type  
<tr><td>&nbsp;1 <td>&nbsp;  -100 +20    <td>&nbsp;  TX Power    Calibrated Tx power at 0 meters. This allows for estimating the distance to the tag.<br>
&nbsp;Max for nordic nRF5832 is 4

<tbody bgcolor=azure>
<tr><td cellpadding=0 colspan=9 style=border-style:none; align=center>URL

<tr><td>2<td><code>00</code>..<code>03<br>
<big>&curren;</big><td colspan=9><b>Protocol</b> <br>
<code><big>&curren;</big></code> codes:<br>  <span style=font-family:monospace><code> 00</code> http://www. , <code>01</code> https://www., <code>02</code> http://, <code>03</code> https:// </pre>

<tr><td>3..<i>i</i><td><code>a</code>-<code>z</code> and <code>-<td><b>           Domain Name</b> (case insensitive, ie translated to lower) 

<tr><td><i>i</i>+1..<i>j</i>  <td><code>&loz; </code>or<br> <code> .c&hellip;<td colspan=9> <b>Top Level Domain</b>  <br>
<code>&loz;</code> codes:<br>
<span style=font-family:monospace><code>00</code> .com&nbsp;    <code>01</code> .org&nbsp;    <code>02</code> .edu&nbsp;     <code>03</code> .net&nbsp;     <code>04</code> .info&nbsp;    <code>05</code> .biz&nbsp;   <code>06</code> .gov&nbsp; <br>
<code>07</code> .com/   <code>08</code> .org/   <code>09</code> .edu/    <code>0a</code> .net/    <code>0b</code> .info/         <code>0c</code> .biz/       <code>0d</code> .gov/ </span><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;or<br>
<code>a..zz</code>   text characters to specify other (case insensitive) TLD, for example <code>.fi,.us,.edu,.vi,.io,.tv,.news &hellip;</code> &nbsp;
<tr><td>&nbsp; <i>j</i>+1&hellip;20<td colspan=1><code>c&hellip;<td>Beacon Data Characters  (Application dependent)

</table>





<h2 style=margin-bottom:0>ruuvi Beacon Data Formats for sample Application: Environment  Station</h2>  <small>(doesn't really tell [let alone predict] weather [rain,sunlight&hellip;)</small><p>
The web server address is nearly minimal <code><big>&curren;</big>ruu.vi/</code> Where the <code><big>&curren;</big></code> is the protocol code x'<code>03</code>' for <code>https://</code> 
This allows only 10 characters for the beacon data which must be printable and cannot contain most special characters 
<small>(an address of the form <tt>XYZ.com/</tt> or <tt>XYZ.info/</tt> would allow 12 characters since a code could be used for the TLD and slash)</small>.<p>

The beacon data is encoded to allow the maximum amount of data. A base 64 scheme is used. This causes 3 bytes to expand to 4 charactersbytes ; 6 bytes expands to 8 characters. When viewing the packet with a diagnostic tool or the URL in the address bar of a browser it is this string of characters which is visible.

<p>

Formats 1-7 are prefixed with the fragment identifier introducer (<code>#</code>) allowing only 9 actual beacon data characters. The <code>#</code> appears to immediately follow the <code>/</code> from the web page viewpoint.
 For example: <code>ruu.vi/#BnALAMNQr</code><br>
This allows the default web page, <code>index.html</code>, to provide the decoding algorithim and page formatting.<br>
The data from the beacon is specified as the fragment identifier. 
Since the fragment is NOT transmitted, the web site cannot process any information other than the time and  IP address.

<p>

<ul>Format type codes:
<table border=1 cellspacing=0 cellpadding=2>
<tr><Td><code>#0 <td>unused as of the date of this document
<tr><Td><code>#1   <td><small style=color:gray>Historical  deprecated</small>
<tr><Td><code>#2   <td><a href=#two>Eddystone-URL</a>, URL-safe base64 -encoded, kickstarter edition (no battery voltage)
<tr><Td><code>#3  <td> <a href=#three>BLE Manufacturer</a> specific data, base 92 encoded, all current sensor readings at 1 second interval
<tr><Td><code>#4 <td>  <a href=#four>Eddystone-URL with tag ID. </a>, URL-safe base64 -encoded, 
<tr><Td><code>#5 <td>and greater are  unused &hellip;
<!--               URL/? <-userID follows (actual values prevents browser from caching multiple page -->
<!--  DGG format temp range -20&hellip;120 F, not fractions not that accurate!, P 29-32inHg in ? -->
</table>

<p>
Formats that do not include the  fragment (<code>#</code>) identifier introducer allow for 10 beacon data characters or 6 binary data bytes.<br>
This means that the web page must be the 404 error handler since the data from the beacon will not specify an existing page.  
<p>

<table border=1 cellspacing=0 cellpadding=2>
<tr><td align=right><code>  4         <td align=right><code>x04   <td>+ 2 bits of battery status <td>&nbsp;
<tr><td align=right><code>  8-12     <td><code> x08-0C   <td><td>                         +  1 bits (i.e x04) of&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
<tr><td align=right><code> 16-28     <td><code> x10-1C   <td><td>                         +  2 bits of  
<tr><td align=right><code> 32-59     <td><code> x20-3C   <td><td>                         +  3 bits of 
<tr><td align=right><code> 64-123    <td><code> x40-7C   <td><td>                         +  4 bits of 
<tr><td align=right><code>128-251    <td><code> x80-FC   <td><td>                         +  5 bits of  
</table>
Errors are indicated by "special" values: initialization failure, value xxx exceeds limit<p>
As there are a limited number of format types available without sacrificing bits for data, a change in format type is only necessary when the format is incompatible. 
For example using previously unused bits will not be reason to change the format type code. 
This means that if a field has a range of 0-124, is right justified in a byte and is in a field documented to be 7 bits wide do not assume that the high  order bit will be zero.



<!--    not as good an idea :
<ul>
<pre>
<li><span style=color:gray> 0         x00  no error bits (bad)</span>
<li><span style=color:gray> 1         x01  no error bits (bad)</span>
<li><span style=color:gray> 2         x02   + 1 bit </span>
<li><span style=color:gray> 4         x04   + 2 bits</span>
<li><span style=color:gray> 8-15      x08-0F  3 bits of error (oops) </span>
<li>16-31      x10-1F  4 bits of error 
<li>32-63      x20-3F  4 bits of error and 1 bit for  
<li>64-127     x40-7F  4 bits of error and 2 bits of ?? </b>
<li><b>128-255    x80-FF  4 bits of error and 3 bits of ??? </b></b>
</pre>
</ul>
Error bits: initialization failure, battery low, value xxx exceeds limit
</pre>
-->


<style>i {font-family:monospace;font-weight:bold;font-size:100%;color:navy}</style>
<p>
The decoded, binary array is referred to as b[<i>i</i>] and the bit numbers are shown as <code>.</code><i>ijk</i>&hellip;
<br>
For example, a reference to the first byte, the low order bit is: <code>b[0].7</code> aka <tt>b'0000 0001'</tt>.



<table border=1 cellspacing=0 cellpadding=5 style=border-color:lime>

<tr> <td colspan=1>format type code <td>value        <td> intrepretation  
<tr><td bgcolor=lime><code style=font-size:150%>8  </code><td><td style=background-color:lime><code>if ( b[0] & 0xF8 == 08 )</code>  uses <tt>ruu.vi/404_index.html</tt> to intrepret and display
        <tr><td><code>b[0].0123        <td>     &iquest;      <td>   reserved for future use
        <tr><td><code>b[0].4      <td> <tt><small>1</small></tt>    <td>   format type code  <code> ( b[0] & 0xF8 == 08 )</code>
        <tr><td><code>b[0].5        <td>     &iquest;      <td>   reserved for future use
<tbody bgcolor=cornsilk>
        <tr><td><code>b[0].67        

        <td ><code>0..3<td><big>Battery status </big><br>
                    <code>bstat=b[0] & 03</code>
                    <table cellspacing=0 cellpadding=2 border=1 style=border-style:dotted;border-color:gray>
                      <tr><td><code>  0 <td>  OK<td>&nbsp;
                      <tr><td><code>  1  <td>  notice  <td>   sensor update and transmission frequency reduced
                      <tr><td><code> 2   <td> critical <td> <code> b[4]</code> hours since notice (no air pressure data)
                      <tr> <td><code> 3   <td> emergency <td> (low or cannot read battery sensor)<br>
                                         no sensors polled<br>
                                         <code>b[1]</code> hours since critical (no humidity data, no air presssure data) 
                    </table>





<tr><td><code> b[1].234567 <td><code>    0..63 <td><big>  Humidity</big>    <br> 
                                                    1 = 2%      As environment station humidity more precision is not meaningful .<br>
                    <nobr><code>hum= ( b[1] & 0x3F ) *2</code><nobr> <br>
                    Errors       :
                    <table cellspacing=0 cellpadding=2 border=1 style=border-style:dotted;border-color:gray>
                    <tr><td><code>   60  <td> sensor could not be read
                    <tr><td><code>   62  <td> value greater than  maximun expected
                    <tr><td><code>   63  <td>   sensor could not be initialized 
                    </table>
<small>(Users who need humidity more precision undoubtedly
                                                            need their own firmware for other reasons and 
                                                                display to a web page will not be sufficient.)</small>

<tbody bgcolor=mistyrose>
        <tr><td><code>b[1].01    <td><code>     0..3    <td>     change in temperature since 1 hour  ago, 1:= was less then now, 2:= was greater,<br>
                                                                              0:= no change, 3:= sensor had an error then

<tbody>
<tr><td><code> b[2].0       <td><code>  0..1     <td>  &iquest;

<tbody bgcolor=mistyrose>

<tr><td><code>        b[2].1234567 <td><code>  0..125  <td><big>Temperature &deg;C  </big>  <br>
Biased at -30. Range -30..85&deg;C  ( span 115 ) aka:   ( -22..183 &deg;F ) <br>

                                  <code>degc = ( b[2] & 0x7F)  -30 </code><br>
    Errors:
            <table cellpadding=2 cellspacing=0 border=1  style=border-style:dotted;border-color:gray> 
                <tr><td><code>124        <td> sensor could not be read
                <tr><td><code>125        <td> value less than minimun expected
                <tr><td><code>126        <td> value greater than  maximun expected
                <tr><td><code>127        <td>temperature sensor failed to initialize

                </table>

<small>(Users who need more precise temperature undoubtedly need their own firmware for other reasons&hellip;</small> 

<tbody>
<tr height=100><td> <code>b[3]          <td><code>0..255 <td> &nbsp &iquest;



<tbody bgcolor=lightblue>
<tr><td> <code>b[4].0123      <td><code>0..63          <td><big>Air pressure  in pa</big>
                                                    <br> biased at 990   range 990..1040<br>
                                        <code>pa = ( b[4] >>8 ) + 990</code> 
                <table cellpadding=2 cellspacing=0 border=1  style=border-style:dotted;border-color:gray>
                <tr><td colspan=2>errors
                <tr>                  <td><code>60          <td> sensor could not be read 
                <tr>                  <td><code>61          <td>  value less than minimun expected
                <tr>                  <td><code>61          <td> value greater than  maximun expected
                <tr>               <td><code>63          <td>error sensor failed to initialize
                </table>
<small>(Users who need  larger range undoubtedly need &hellip; )</small>

        <tr><td><code>b[4].45         <td><code>0..3   <td>      Change in pressure since 2 hours ago
                    <table cellspacing=0 cellpadding=2  border=1 style=border-style:dotted;border-color:gray>
                    <tr><td><code>0<td>&nbsp; no change
                    <tr><td><code>1<td>&nbsp; pressure was less then it is now
                    <tr><td><code>2<td>&nbsp; pressure was greater
                    <tr><td><code>3<td>&nbsp; pressure sensor had an error then
                    </table>
        <tr><td><code>b[4].67         <td><code>0..3      <td>   Change in pressure since 4 hours ago
                <table cellspacing=0 cellpadding=2  border=1 style=border-style:dotted;border-color:gray>
                <tr><td><code>0<td>&nbsp; no change
                <tr><td><code>1<td>&nbsp; pressure was less then it is now
                <tr><td><code>2<td>&nbsp; pressure was greater
                <tr><td><code>3<td>&nbsp; pressure sensor had an error then
                </table>
<tbody bgcolor=lavender>

<tr><td> <code>b[5..6]    <td><code>   1..65535    <td>  ID of TAG taken from  of nRF5283 . DEVICEID[0] low order 16 bits
</table>

<table border=1 cellspacing=0 cellpadding=2>
<tbody bgcolor=lemonChiffon>
<tr id=three><td valign=top><big>
<code>#3
<td colspan=9>
For users who need more precision.<p>
Does not contain URL and is not used by the <code>ruu.vi</code> web page. Requires custom reader/interpreter.<br>
Protocol Specification <a href=https://github.com/ruuvi/ruuvi-sensor-protocols>github ruuvi/ruuvi-sensor-protocols</a>
                             <a href=https://github.com/ojousima/sensor-protocol-for-eddystone-url/tree/feature-sensortag>github ojousima/sensor-protocol-for-eddystone-url/tree/feature-sensortag</a>

<p>
The data is encoded in non-standard base92 (some reserved like ?#%@$).<br>

plain Sensor Tag sends the data as Manufacturer specific data in undirected, non-connectable bluetooth advertisement.  <br>

Data is decoded from "Manufacturer Specific Data" -field, article out. Manufacturer ID is 0xFFFF (not specified - /TODO).  <pre>
Offset  values  Description
0         3   
1     0 &hellip; 200   Humidity (one lsb is 0.5%, example: 128 is 64%)
2  -40 &hellip; 85   Temperature (MSB is sign, next 7 bits are value <small>(akward?)</small> centigrade. 
<!-- Note:127 is 27&degree; over boiling! -->
3     0 &hellip; 99    Temperature (fraction, 1/100.)
4-5   300 &hellip; 11000 air Pressure (Most Significant Byte first, value 0000 - 50kPa)
6-7   -16000 &hellip; 16000, signed    Acceleration-X (Most Significant Byte first)
8-9   -16000 &hellip; 16000, signed    Acceleration-Y 
10-11 -16000 &hellip; 16000, signed    Acceleration-Z 
12-13 0 &hellip; 3600 Battery voltage (millivolts). 
</pre>
<h3>Data field descriptions</h3>
<table border=1 cellspacing=0>

<tr><td> <b>Humidity</b> : 0% to 100% in .5% increments.  <br>
Value:Measurement; x0000:0% ; 128:64% ; 200:100%   <span style=color:tan>; 255 error to   be implemented </span>
<tr><td><b>Temperature</b>: -127.99&degC to +127.9 &deg;C (well over boiling!) in .01&deg;C increments.<br>
Value:Measurement; x0000:0&deg;C  ; x8145:-1.&deg;C;  x0145:1 &deg;C 
<tr><td><b> Atmospheric Pressure</b>  <br>
50,000 Pa to 115,536Value   Measurement:  Pa in 1 Pa increments.   <small>  (1003-1026 range found by scrin  https://graphs.2kgwf.fi/dashboard/db/ruuvi-demo)</small><p>
Value:Measurement; 0-50000 Pa; 41325:101325 Pa (average sea-level pressure)  ; 65534:115534 Pa <span style=color:tan>; 65535 error to be implemented </span>
<tr><td> <b>Acceleration </b>-32000 to 32000 (mG), 16 G max (2 G in default configuration). <BR>
                    Values are 2-complement int16_t, 3 channels X,Y,X <BR>
Value:Measurement; 0xFC18:-1000 mG  ; 0x03E8:1000 mG  <span style=color:tan>; 65535 error to   be implemented </span>
<tr><td> <b>Battery voltage</b> 
1800 mV to 3600 mV in 1 mV increments,  accuracy?  <span style=color:tan>; 1000 error to  be implemented </span>
</table>

ToDo: "special" values to indicate error.

<!--  private DGG never built
<tr><td valign=top>7 <td colspan=9><pre>
                8xxx  10 EE 02  j  -  0  0b x1 x2 x3 x4 x5 x6 x7 x8 x9 xA    (room for  more characters than fmt 4)
                            |                       |                                             no  'vi/#A'  (version is part of J-n.INFO
                            `---http://              `- .info/                                                  
                       1  2  3   4  5  6  7  8  9  10 11 12 13 14 15 16 17 18 19 20 ??
                                                       x1-x9 are environment data base 92
                                            temp biased off -30C(-22F)                             1 base 92 digit  ! thru ~
                ! "#$%&hellip;   ( > -22+15=-7C(19F) &hellip; @ -30+31= 1C(33F) , A,, Z,,, a,,,z {|}    ~ -30+92=60C(140F) 
                                            humidity biased off 6%                                 1 base 92 digit  ! thru ~
                                                                     ! >6%,     ~ >100%            
                                            delta pressure ! thru / period -5 minutes,   0 > no change, / 1 unit drop, . 2, - 3, , 4, + 5
                                                                                                        1 1 unit rise, 2 2, &hellip; 
                                                            4 bits provides -7&hellip;7 delta pressure for period of  6 periods of (_) minutes
                                                        ! &hellip; 0 first period delta 0-15 all other periods 
                                                        G       first period delta 0, second period delta 0
                                                        @       first period delta 0, second period delta -7
                                                        A       first period delta 0, second period delta -6
                                                        B                                                 -5
                                                        H                                                 1
                                                        O                                                 8
                            ie P  base 16    pn                              *16**3 +   pn-1  *16**2  +  pn-2 *16**1 +   pn-3 *16**0 i.e. 1
                                 P0F[ ]       0 > -7                            
                                              1 > -6
                                              2,3,4,5,6,   -5,-4,-3,-2,-1
                                              7 > 0
                                              8,9,A,B,C,D,E,F 1,2,3,4,5,6,7,8

example     7777   divide by 16, P0F[remainder] ,  dividend / 16  P0F[remainder], dividend/16 P0F[rem]  , P0F[dividend]
                                P0F[7] = 0     ,        P0F[7] = 0                  P0F[7]=0               P0F[7] = 0
            805F                P0F[F] = +8    ,        P0F[5] = -2                 P0F[0]=-7              P0F[8] = +1

-->










<tbody bgcolor=paleGoldenrod>
<tr id=four><td><code>#4<td colspan=9> same as version 2 with the addition of the trailing ID byte<pre> 6       0..255 &iquest;     id of tag   4/17/17
                transmitted text example: <code>B  n  A  L  A  M  N  Q  N    </pre> 

<tr id=two><td>
<code>#2 
<td colspan=9> Uses <code>ruu.vi/index.html</code> web page to intrepret and display. <pre>
Offset  range       Description
0       2        format: current sensor readings for URL
1       0 &hellip; 200  Humidity (one lsb is 0.5%, e.g. 128 is 64%)
2     -40 &hellip; 85  <a href=https://www.bosch-sensortec.com/bst/products/all_products/bme280>Temperature</a> (MSB is sign, next 7 bits are decimal value) signed    
3       0          Temperature Fraction, 1/100.). set to ZERO because <b>nearby</b> causes notification on slight changes.
4 - 5 300 &hellip;1100 Pressure (Most Significant Byte first, value 00 - 50kPa). Rounded to 1 hPa precision

        1  2  3   4  5  6  7  8  9  10 11 12 13 14 15 16 17 18 19 20 
       10 EE 03   72 75 75 2E 76 69 2f 23 41 6e 41 4c 41 4d 4e 51    <small> from <a href=nordic.com/ >nRF connect</a>  service data</small>
             |    r  u  u  .  v  i  /  #  <code>A  n  A  L  A  M  N  Q</code>   =   11C  56%  1000kpa
             `---https://                 ft x1 x2 x3 x4 x5 x6 x7 x8 </pre>

</table>

URL defined: <code>scheme://[user[:pass]@]host ?  #fragment           </code> <p>

from <tt>https://github.com/ruuvi/ruuvi-sensor-protocols/blob/master/README.md</tt>
<p>
on power up or button press:
<tt>https://github.com/google/eddystone/blob/master/eddystone-url/docs/config-service-spec.md </tt>
<table width=100%><tr><td align=right><small>version 17/08/17 dgg

</body>
</html>
