# K-Note
Glad you test it and submit bugs

BUG List:

When the window maximized, and the text box layout is terrible (Solution: determine the maximum, force the position size) **[Fixed]**

Drag and drop files to read, an error occured when save closing  (Reason: filename is set to null) **[Fixed]**

Error when canceling file selection (Solution: else not selected) **[Fixed]**

Multi-language resx can't be contained in the exe (Solution: published by ClickOnce (Application File... -> contain /zh-CN/K-Note.resources.dll.deploy)) **[Fixed]**



**Need to achieve**
Fix hot keys listview column width
Add ClickOnce certificate
Optimize the value-passing method (currently create a new object)
