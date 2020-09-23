<div align="center">

## Use Index Server to do full text extraction on PDF files


</div>

### Description

I call this the $25K solution because that's how much the next cheapest alternative was going to cost this company I was working for. Actually, we found alternatives for over $150,000 and these other solutions only purhased the site licences- no configuration, no development, no free upgrades! So the next time somebody asks you if you're worth $100 an hour, tell them that you're the expert that can help them save money! Then tell them this story...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Glenn Cook](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/glenn-cook.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Server Side](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/server-side__4-31.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/glenn-cook-use-index-server-to-do-full-text-extraction-on-pdf-files__4-6210/archive/master.zip)





### Source Code

<p><font face="Verdana"><strong>The Ifilter is back at Adobe! <small>Over the
past two months it was removed from Adobe's site because of trade embargo
restrictions.&nbsp; ASP Trencher, G. Jurgele, informed me that it is available
again at the FTP site and will be available on their website soon.&nbsp; Here
are the URL's.</small></strong></font><u><font color="#0000ff" size="2">
<ul>
 <li><font face="Verdana">http://www.adobe.com/prodindex/acrobat/ifilter.html</font>
 <li></font><font color="#0000ff" face="Verdana" size="2">ftp://ftp.adobe.com/pub/adobe/acrobat/win/all/</font><font color="#0000ff" size="2"></li>
</ul>
</font></u>
<p><font face="Verdana" size="2">Skip to <a href="http://www.planet-source-code.com/vb/scripts/ShowCode.asp?lngWId=4&amp;txtCodeId=6209">&quot;The
Index Server Tutorial&quot;</a></font></p>
<p><font face="Verdana" size="2">I call this the $25K solution because that's
how much the next cheapest alternative was going to cost this company I was
working for. Actually, we found alternatives for over $150,000 and these other
solutions only purhased the site licences- no configuration, no development, no
free upgrades!&nbsp; So the next time somebody asks you if you're worth $100 an
hour, tell them that you're the expert that can help them save money! Then tell
them this story:</font></p>
<p><font face="Verdana" size="2">OBJECTIVE: Provide web-based full text
searching on thousands of pdf files for a major car manufacturer's Intranet.&nbsp;
WindowsNT is the server platform of choice.</font></p>
<p><font face="Verdana" size="2">PROBLEM: This Intranet/Extranet was going to be
designed to support dealerships nationally with important up-to-date technical
bulletins.&nbsp; In the past two years they had compiled thousands of pdf files
which they were indexing with Adobe's Acrobat and they would burn CD's quarterly
for all the dealerships.&nbsp; This means that real imortant updates would have
to be sent by Fed-X for delivery the next day in paper format which would often
end up misplaced, destroyed, or just plain impossible for the mechanics to find.</font></p>
<p><font face="Verdana" size="2">SOLUTION: Adobe's <a href="http://www.adobe.com/prodindex/acrobat/ifilter.html">&quot;PDF
Ifilter DLL&quot;</a>! When we found it on Adobe's website, noone knew about it.&nbsp;
We talked with the Adobe Engineers who referred us to companies that had $25K
plus solutions for what we needed.&nbsp; Microsoft's Engineers also referred us
to expensive alternatives. &nbsp; When we found this needle in a haystack we
couldn't believe noone knew about it. &nbsp; Microsoft referred to it briefly on
a couple web pages and Adobe referred to it on three pages but it was barely
documented and not suported by either.&nbsp; It was funny when the Adobe
salesperson called a week later and we told them that we were using one of their
DLL's as a solution.&nbsp; He blew his lid because he was in the process of
setting up meetings with other vendors for us.&nbsp; He was also embarrassed
that none of THEIR engineers that we talked to knew about it.</font></p>
<p><font face="Verdana" size="2">You'll notice that Adobe is working on a beta
DLL that works with IIS 4.0.&nbsp; There is also improved documentation and more
referrences to it on their site.&nbsp; Unfortunately the PDF Ifilter 1.0 ONLY
works with Index Server 1.0 and IIS 3.0.&nbsp; The IIS4.0 beta is available as
well.</font></p>
<p><font face="Verdana" size="2">The ifilter.exe file registers a dll in seconds
and voila, Index server amazingly picks apart those darn pdf files.&nbsp; Enjoy!</font></p>
<p><font face="Verdana"><font size="2">Now, go learn how to make index server
work for you!&nbsp;</font><font size="1"> </font><font size="3"><strong><a href="http://www.planet-source-code.com/vb/scripts/ShowCode.asp?lngWId=4&amp;txtCodeId=6209">It's
here</a> ( In its &quot;draft&quot; stages!)</strong></font></font></p>

