
<%*
 let title = tp.file.title
 if (title.startsWith("Untitled")) {
  title = await tp.system.prompt("Title");
  await tp.file.rename(title);
 } 
 tags = await tp.system.prompt("Subject/Topics")
 tR += "---"
%>
Title:  <%* tR += title %>
Created: <% tp.date.now("dddd Do MMMM YYYY HH:mm") %>
Topic: <%* tR += title %>
Aliases: 
Tags: <% tp.file.creation_date('MM-YYYY') %>, <%* tR += title %>, <%* tR += tags %>
Type: Note
Author: Christian Flores 

---

#  [<%* tR += title %>]
Author: [[Christian Flores]]
[ ](#anki-card)
## 📝 Notes
- 


## Questions/Thoughts
- 
## 🔗 Links
- 