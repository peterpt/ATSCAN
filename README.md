<html>
<body>
<h1 align="center">ATSCAN</h1>
<p align="center"> <b>Search / Site / Server Scanner </b></p>
<center><img src="http://i.imgur.com/jUt3Gn7.png" /></center>
<table border="0" cellpadding="2" cellspacing="2" width="100%">
  <tr>
    <td align="center"><b>Alisam Technology is not responsible for any misuse, damage caused by this script or attacking targets without prior mutual consent!<b></td>
  </tr>
</table>
<table border="0" cellpadding="0" cellspacing="2" width="100%">
  <tr>
    <td width="100px" class="main2"><b>AUTHOR:</b></td><td width="780px">Alisam@Technology</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>FACE:</b></td><td>facebook.com/Forces.des.tempetes.marocaines </td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>YOUTUBE:</b></td><td>youtube.com/c/AlisamTechnology</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>WITTER:</b></td><td>twitter.com/AlisamTechno</td>
  </tr>
  <tr>
    <td width="100px" class="main2"><b>PLUS:</b></td><td>plus.google.com/+AlisamTechnology</td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3"><b>Description:</b></td>
  </tr>
  <tr>
    <td class="main" width="890px">ATSCAN <br /> SEARCH engine <br />XSS scanner. <br /> Sqlmap.<br /> 
        LFI scanner.<br /> Filter wordpress and Joomla sites in the server. <br />Find Admin page.<br /> Decode / Encode MD5 + Base64.
    </td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3" width="890px"> <b>Libreries to install:</b></td>
  </tr>
  <tr>
    <td class="main">
      ap-get install libxml-simple-perl <br/>
      aptitude install libio-socket-ssl-perl <br/>
      aptitude install libcrypt-ssleay-perl <br/>
      NOTE: Works in linux platforms. Best Run on Ubuntu 14.04, Kali Linux 2.0, Arch Linux, Fedora Linux, Centos | if you use a windows you can download manualy.
    </td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3" width="890px"><b>Download & Executution:</b></td>
  </tr>
  <tr>
    <td class="main">
      git clone https://github.com/AlisamTechnology/ATSCAN <br/>
      cd ATSCAN <br/>
      chmod +x ATSCAN <br/>
      ./ATSCAN <br/>
      OR <br/>
      $chmod +x atscan.pl  <br/>
      Execute: perl ./atscan.pl <br/>
      Execute: perl ./atscan.pl --help
    </td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3"><b>Screenshots:</b></td>
  </tr>
  <tr>
    <td align="center" width="890px">
    <img src="http://i.imgur.com/GlsitTn.jpg" /><br/><br/>
    <img src="http://imgur.com/cydQiB9.jpg" /><br/><br/>
    <img src="http://i.imgur.com/4cqbGNW.jpg" /><br/><br/>
    <img src="http://i.imgur.com/c7ePRIq.jpg" /><br/><br/>
    <img src="http://i.imgur.com/YtPr5OF.jpg" /><br/><br/>
    <img src="http://i.imgur.com/Ppg5Pez.jpg" /><br/><br/>
    <img src="http://i.imgur.com/MKDYjVo.jpg" /><br/><br/>
    </td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td class="main3" width="890px"><b>Help:</b></td>
  </tr>
  <tr>
    <td class="main"><table border="0" cellpadding="2" cellspacing="5" width="100%">
      <tr>
        <td width="200px" class="main">--proxy</td>
        <td width="680px">tor proxy [DEFAULT:socks://localhost:9050] Change if needed!</td>
      </tr>
      <tr>
         <td width="200px" class="main">--dork</td>
        <td class="main">Search engine</td>
      </tr>
      <tr>
        <td width="200px" class="main">--level</td>
        <td class="main">set scan level (more hight more sersults)</td>
      </tr>
      <tr>
        <td width="200px" class="main">--xss</td>
        <td class="main">Xss scan</td>
      </tr>
      <tr>
        <td width="200px" class="main">--lfi</td>
        <td class="main">lfi scan</td>
      </tr>
      <tr>
        <td width="200px" class="main">-t</td>
        <td class="main">Target</td>
      </tr>
      <tr>
        <td width="200px" class="main">-l</td>
        <td class="main">List name</td>
      </tr>
      <tr>
        <td width="200px" class="main">--exp</td>
        <td class="main">Set exploit</td>
      </tr>
      <tr>
        <td width="200px" class="main">--valid</td>
        <td class="main">Text for validate results</td>
      </tr>
      <tr>
        <td width="200px" class="main">--sqlmap</td>
        <td class="main">Sqlmaping xss results</td>
      </tr>
      <tr>
        <td width="200px" class="main">--lfi</td>
        <td class="main">local file inclusion</td>
      </tr>
      <tr>
        <td width="200px" class="main">--joomrfi</td>
        <td class="main">get joomla sites with rfi in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--shell</td>
        <td class="main">shell link [Ex: http://www.site.com/shell.txt]</td>
      </tr>
      <tr>
        <td width="200px" class="main">--wpadf</td>
        <td class="main">get wordpress sites with arbitery file download in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--admin</td>
        <td class="main">get site admin page</td>
      </tr>
      <tr>
        <td width="200px" class="main">--shost</td>
        <td class="main">get site subdomains</td>
      </tr>
      <tr>
        <td width="200px" class="main">--ports</td>
        <td class="main">scan server ports</td>
      </tr>
      <tr>
        <td width="200px" class="main">--start</td>
        <td class="main">start scan port</td>
      </tr>
      <tr>
        <td width="200px" class="main">--end</td>
        <td class="main">end scan port</td>
      </tr>
      <tr>
        <td width="200px" class="main">--all</td>
        <td class="main">complete mode</td>
      </tr>
      <tr>
        <td width="200px" class="main">--basic</td>
        <td class="main">basic mode</td>
      </tr>
      <tr>
        <td width="200px" class="main">--select</td>
        <td class="main">Select mode you can set rang of ports</td>
      </tr>
      <tr>
        <td width="200px" class="main">--sites</td>
        <td class="main">sites in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--wp</td>
        <td class="main">wordpress sites in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--joom</td>
        <td class="main">joomla sites in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--upload</td>
        <td class="main">get sites with upload files in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--zip</td>
        <td class="main">get sites with zip files in the server</td>
      </tr>
      <tr>
        <td width="200px" class="main">--st</td>
        <td class="main">string</td>
      </tr>
      <tr>
        <td width="200px" class="main">--md5</td>
        <td class="main">convert to md5</td>
      </tr>
      <tr>
        <td width="200px" class="main">--encode64</td>
        <td class="main">encode base64 string</td>
      </tr>
      <tr>
        <td width="200px" class="main">--decode64</td>
        <td class="main">decode base64 string</td>
      </tr>
      <tr>
        <td width="200px" class="main">--isup</td>
        <td class="main">check http status 200</td>
      </tr>
      <tr>
        <td width="200px" class="main">--httpd</td>
        <td class="main">print site httpd version</td>
      </tr>
      <tr>
        <td width="200px" class="main">--update</td>
        <td class="main">Check for update</td>
      </tr>
      <tr>
        <td width="200px" class="main">--replaceme</td>
        <td class="main">string to replace</td>
      </tr>
      <tr>
        <td width="200px" class="main">--withme</td>
        <td class="main">string to replace with</td>
      </tr>
    </table></td>
  </tr>
</table>
<table border="0" cellpadding="2" cellspacing="5" width="100%">
  <tr>
    <td width="890px"><b>Examples:</b></td>
  </tr>
  <tr>
    <td class="main">
    <b>Simple search: </b><br/>
    --dork DORK --level [Scan level more big more results]<br/>
    --dork [DORK1,DORK2,DORK3..] --level [ex:100]<br/>
    --dork [DORK.txt] --level [Scan level ex: 50]<br/><br/>
    <b>Subscan from Serach Engine: </b><br/>
    Xss: --dork DORK --level 50 --xss<br/>
    Xss: --dork DORK --level 50 --xss --sqlmap<br/>
    Xss: --dork DORKS.TXT --level 50 --xss <br/>
    Lfi: --dork DORK --level 50 --lfi<br/>
    Search + Command:<br/>
      --dork DORK --level VALUE --command 'curl -v' --TARGET<br/>
      --dork <dork/dork.txt> --level <value> --replaceme STRING1 --withme STRING2<br/>
      --dork <dork/dork.txt> --level <value> --replaceme STRING1 --withme STRING2 --isup<br/>
      --dork <dork/dork.txt> --level <value> --replaceme STRING1 --withme STRING2 --valid <txt><br/>
    <b>Validation: </b><br/>
    --dork DORK --level 50 --exp --valid TEXT <br/>
    --dork DORK --level 50 --exp --isup <br/>
    --dork DORKS.TXT --level 50 --exp --valid TEXT <br/>
    --dork DORKS.TXT --level 50 --xss --sqlmap <br/>
    --dork DORKS.TXT --level 50 --exp --isup <br/><br/>
    <b>Use List / Target: </b><br/>
    Xss: -t TARGET --xss <br/>
    Lfi: -l TARGET --lfi <br/>
    Validation: -t TARGET --exp --valid TEXT <br/>
    Validation: -l list.txt --exp --isup <br/>
    Find admin page: -t TARGET --admin  <br/>
    Find subdomains: -t TARGET --shost  <br/><br/>
    
    <b>Server: </b>  <br/>
    Get Server sites: -t IP --level [VALUE] --sites   <br/>
    Get Server sites: -t IP.txt --level [VALUE] --sites   <br/>
    Get Server wordpress sites: -t IP --level [VALUE] --wp   <br/>
    Get Server joomla sites: -t IP --level [VALUE] --joom   <br/>
    Get Server upload sites: -t IP --level [VALUE] --upload   <br/>
    Get Server zip sites files: -t IP --level [VALUE] --zip   <br/>
    WP Arbitry File Download: -t IP --level [VALUE] --wpadf   <br/>
    Joomla RFI: -t IP --level <100> --joomfri --shell SHELL LINK   <br/>
    Scan basic tcp (quick): -t IP --ports --basic tcp   <br/>
    Scan basic udp basic (quick): -t IP --ports --basic udp   <br/>
    Scan basic udp+tcp: -t IP --ports --basic udp+tcp   <br/>
    Scan complete tcp: -t IP --ports --all tcp   <br/>
    Scan complete udp: -t IP --ports --all udp   <br/>
    Scan complete tcp+udp: -t IP --ports --all udp+tcp   <br/>
    Scan rang tcp: -t IP --ports --select tcp --start --end    <br/>
    Scan rang udp: -t IP --ports --select udp --start VALUE --end VALUE   <br/>
    Scan rang udp + tcp: -t IP --ports --select udp+tcp --start VALUE --end VALUE <br/>
    <b>Encode / Decode:  </b> <br/>
    Generate MD5: -st STRING --md5 <br/>
    Encode base64: -st STRING --encode64  <br/> 
    Decode base64: -st STRING --decode64 <br/><br/>
    <b>Check for update: </b>  <br/>
      --update
    </td>
  </tr>
</table>  
</body>
</html>
