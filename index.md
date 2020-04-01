## Welcome to GitHub Pages

![Crystal Lock](/images/crylock.png)


[My Blog](https://www.reboot95.us/wordpress) 
 for your viewing pleasure, where i've become stuck in time
 
 [Old Blog](https://reboot95.blogspot.com)

### Servlet written in Jython.

```python
#test Calendar this is written in jython.!

from javax.servlet.http import HttpServlet
import calendar
import sys
import time

class Cal_old(HttpServlet):
  def processRequest(self,req,res):
    out = res.writer
    
    res.contentType = "text/html"
    out.println("<pre>")
    out.println(calendar.calendar(time.localtime()[0]))
    
  def doGet(self, req, res):
      self.processRequest(req,res)
  def doPost(self,req,res):
      self.processRequest(req,res)

if __name__ =="__main__":
    pass
    #srv = Cal_old()
    #dReq = DummyHttpRequest()
    #dRes = DummyHttpResponse()
    #srv.processReques(dReq,dRes)

```

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

[Repository settings](https://github.com/reboot95/reboot95.github.io/settings). 

[Edit on GitHub](https://github.com/reboot95/reboot95.github.io/edit/master/index.md) 

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
