# October

## Example Incident Name
| Date | Time to Detect | Time to Resolved | Incident Number | Status |
| ---------- | ---------- | ---------- | ---------- | ---------- |
| 2021-10-25 | 1 hour | 2 hours | 123456789 | Resolved |

### Overview
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lobortis elementum nibh tellus molestie. Blandit cursus risus at ultrices mi tempus. Varius sit amet mattis vulputate enim nulla aliquet. Vel eros donec ac odio. Ac odio tempor orci dapibus ultrices in iaculis nunc sed. Viverra vitae congue eu consequat ac felis. Duis ut diam quam nulla porttitor massa id. Mattis ullamcorper velit sed ullamcorper morbi tincidunt ornare massa eget. Dolor sed viverra ipsum nunc aliquet bibendum enim facilisis gravida. Eget magna fermentum iaculis eu non diam phasellus vestibulum. Elit ullamcorper dignissim cras tincidunt lobortis feugiat.

<img src="static/img/october/25/example/grafana.gif" style="max-width: 100%" />


> ERROR: Enim praesent elementum facilisis leo. Elementum facilisis leo vel fringilla. Morbi tincidunt augue interdum velit euismod in pellentesque. Et tortor consequat id porta nibh venenatis. Quam pellentesque nec nam aliquam sem et tortor consequat. Turpis egestas integer eget aliquet nibh praesent. Enim praesent elementum facilisis leo.

Feugiat in fermentum posuere urna nec tincidunt praesent semper feugiat. Consequat interdum varius sit amet mattis vulputate. Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis. Dictum at tempor commodo ullamcorper a lacus vestibulum sed. Lacus sed viverra tellus in hac habitasse platea dictumst. Tellus pellentesque eu tincidunt tortor. Ridiculus mus mauris vitae ultricies leo integer. Varius sit amet mattis vulputate enim nulla. In egestas erat imperdiet sed euismod nisi.

```scala
val dottyVersion = {
    def isNightly = sys.env.get("NIGHTLYBUILD") == Some("yes")
    if (isRelease)
      baseVersion
    else if (isNightly)
      baseVersion + "-bin-" + VersionUtil.commitDate + "-" + VersionUtil.gitHash + "-NIGHTLY"
    else
      baseVersion + "-bin-SNAPSHOT"
  }
  val dottyNonBootstrappedVersion = {
    // Make sure sbt always computes the scalaBinaryVersion correctly
    val bin = if (!dottyVersion.contains("-bin")) "-bin" else ""
    dottyVersion + bin + "-nonbootstrapped"
  }
```

Consequat interdum varius sit amet mattis vulputate. Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis. Dictum at tempor commodo ullamcorper a lacus vestibulum sed. Lacus sed viverra tellus in hac habitasse platea dictumst. Tellus pellentesque eu tincidunt tortor. Ridiculus mus mauris vitae ultricies leo integer. Varius sit amet mattis vulputate enim nulla. In egestas erat imperdiet sed euismod nisi.

### Actions Taken
- Consequat interdum varius sit amet mattis vulputate.
- Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis.
-  Dictum at tempor commodo ullamcorper a lacus vestibulum sed.

### Related Links
- [Alert Slack Thread]()
- [Incident Discussion Thread]()
- [Alert Resolving Notification]()

<br/>

## Example Incident Name 2
| Date | Time to Detect | Time to Resolved | Incident Number | Status |
|---------- | ---------- | ---------- | ---------- | ---------- |
| 2021-10-20 | 2 hour | 2.5 hours | 1234567890 | On-Going |

### Overview
Cras semper auctor neque vitae tempus quam pellentesque. Interdum velit laoreet id donec ultrices tincidunt arcu non. Consequat interdum varius sit amet mattis vulputate enim nulla aliquet. Odio pellentesque diam volutpat commodo sed egestas egestas fringilla. Tortor condimentum lacinia quis vel. Cursus in hac habitasse platea dictumst quisque sagittis purus. Pharetra pharetra massa massa ultricies mi quis hendrerit dolor magna. Pharetra pharetra massa massa ultricies mi quis hendrerit dolor magna. Maecenas sed enim ut sem viverra aliquet eget sit amet. Velit laoreet id donec ultrices. Pellentesque sit amet porttitor eget.
<img src="static/img/october/20/example/grafana.png" style="max-width: 100%" />

Etiam erat velit scelerisque in. Semper eget duis at tellus at urna condimentum mattis. Interdum velit euismod in pellentesque massa placerat duis. Velit dignissim sodales ut eu sem. Amet commodo nulla facilisi nullam vehicula. Faucibus vitae aliquet nec ullamcorper sit. Quis ipsum suspendisse ultrices gravida dictum. Ullamcorper malesuada proin libero nunc. Ornare quam viverra orci sagittis eu. Massa tempor nec feugiat nisl pretium. Diam vel quam elementum pulvinar etiam non. Cursus turpis massa tincidunt dui ut ornare lectus. Consequat ac felis donec et odio pellentesque diam volutpat. Purus gravida quis blandit turpis cursus in hac habitasse. Cras adipiscing enim eu turpis egestas pretium aenean. Urna id volutpat lacus laoreet non curabitur gravida.

> ERROR: Orci dapibus ultrices in iaculis nunc sed. Nulla malesuada pellentesque elit eget gravida cum. Euismod nisi porta lorem mollis aliquam ut porttitor leo. Mi quis hendrerit dolor magna. Eleifend mi in nulla posuere sollicitudin. Scelerisque viverra mauris in aliquam sem fringilla ut morbi tincidunt.

Quis enim lobortis scelerisque fermentum dui. Viverra justo nec ultrices dui sapien eget. Faucibus et molestie ac feugiat sed lectus vestibulum mattis ullamcorper. Sagittis id consectetur purus ut. Sagittis eu volutpat odio facilisis mauris sit amet massa vitae. Pellentesque pulvinar pellentesque habitant morbi tristique senectus. In massa tempor nec feugiat. Faucibus interdum posuere lorem ipsum. Scelerisque viverra mauris in aliquam. Feugiat in fermentum posuere urna nec tincidunt praesent semper feugiat. Consequat interdum varius sit amet mattis vulputate. Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis. Dictum at tempor commodo ullamcorper a lacus vestibulum sed. Lacus sed viverra tellus in hac habitasse platea dictumst. Tellus pellentesque eu tincidunt tortor. Ridiculus mus mauris vitae ultricies leo integer. Varius sit amet mattis vulputate enim nulla. In egestas erat imperdiet sed euismod nisi.


### Actions Taken
- Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis.
- Dictum at tempor commodo ullamcorper a lacus vestibulum sed.

### Related Links
- [Alert Slack Thread]()
- [Incident Discussion Thread]()
- [Alert Resolving Notification]()
