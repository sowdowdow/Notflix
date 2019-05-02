# Notflix
A service listing the latest movies available on different providers (i.e. Zone T.)

## Interest
Retrieving and synthetizing most important elements :

| Title | Description | Mark | Link |
|:-------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------:|:----:|:------------------:|
| The Secret Life of Walter Mitty | Walter Mitty is a negative assets manager at Life magazine who daydreams  of adventures and has a crush on a coworker named Cheryl... | **** | http://example.com |

The movies mark could be an average of multiple `providers` (i.e. Allociné)
## Evolution
- Direct Download / Torrent mixin
- UI
- Switchable architecture : `Client` or `Client / Server`
## Diagramming
```
                                +-----------------+
                                |APP CORE         |
+---------------+               |                 |
|Movies Provider+<--------------+  - Autoload     |
+---------------+               |                 |
                                |  - Fetch async  |
+---------------+               |                 |
|Marks Provider +<--------------+                 |
+---------------+               +--------+--------+
                                         |
                                         |
                                +--------+--------+
                                |CLI(Python Cmd)  |
                                |                 |
                                +-----------------+

```
## Technologies
- Python
- Tkinter ?
- Scrappy ?

### Tools
 - http://asciiflow.com/ for the Scheme
 - https://www.tablesgenerator.com/markdown_tables for the table
