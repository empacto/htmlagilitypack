# htmlagilitypack CheatSheet
Htmlagilitypack is a powerfull HTML scraping/editing tool. This repo, aims to resume in a simple and complete manner locating/editing of individual/group htlm elments in c#. 

A) Setup reference to a specific HTML Page 
1) A public website :
 HtmlDocument doc = new HtmlDocument();
        doc.Load("http://www.google.com");

B) A private webiste (you control):

 CallFunction(Server.MapPath("./yourpage.html")); 
  ./ = c# file is located in the same dir / webserver
    protected void replaceSCR(string html)
    {
    HtmlDocument doc = new HtmlDocument();
        doc.Load(html);
        }
        
 
C) Locating specific individual HTML elements : 

Individual elements can be located by there id or class: 

1) href
2) a
3) li
4) img
5) scr
6) input
7) div
8) 











