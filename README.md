<div align="center">

## \_ Function that stops people from trying to view your page INSIDE a frame \_


</div>

### Description

<br><b>SUPER EASY!</b><br>

<br>

The reason i wrote this was to stop people from trying to put my site in THEIR frameset<br>This code makes it impossible for people to do that! <br>
 
### More Info
 
NOTHING 

----

> its all cut and paste.

even the HTML.

cut and paste even the HTML


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[paul\_cormie](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/paul-cormie.md)
**Level**          |Intermediate
**User Rating**    |4.0 (56 globes from 14 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/paul-cormie-function-that-stops-people-from-trying-to-view-your-page-inside-a-frame__2-2022/archive/master.zip)





### Source Code

```
<html>
<head>
<title>Just try to put his in a frameset!</title>
</head>
<script language="Javascript">
<!--Javascript Start --
if (top.location != self.location) {
	top.location = self.location.href
}
//--Javascript End-->
</script>
<body>
try to put this page in a frameset!.<br><br><br>
it won't work.<p> ;-)
</body>
</html>
```

