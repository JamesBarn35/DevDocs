# September

## Example Incident Name
| Date | Time to Detect | Time to Resolved | Incident Number | Status |
| ----------- | ---------- | ---------- | ---------- | ---------- | 
| 2021-09-15 | 1.5 hour | 2 hours | 0123456789 | Resolved |

### Overview
Blandit cursus risus at ultrices mi tempus. Varius sit amet mattis vulputate enim nulla aliquet. Vel eros donec ac odio. Ac odio tempor orci dapibus ultrices in iaculis nunc sed. Viverra vitae congue eu consequat ac felis. Duis ut diam quam nulla porttitor massa id. Mattis ullamcorper velit sed ullamcorper morbi tincidunt ornare massa eget. Dolor sed viverra ipsum nunc aliquet bibendum enim facilisis gravida. Eget magna fermentum iaculis eu non diam phasellus vestibulum. Elit ullamcorper dignissim cras tincidunt lobortis feugiat.

> ERROR: Enim praesent elementum facilisis leo. Elementum facilisis leo vel fringilla. Morbi tincidunt augue interdum velit euismod in pellentesque. Et tortor consequat id porta nibh venenatis. Quam pellentesque nec nam aliquam sem et tortor consequat. Turpis egestas integer eget aliquet nibh praesent. Enim praesent elementum facilisis leo.
 
Quis enim lobortis scelerisque fermentum dui. Viverra justo nec ultrices dui sapien eget. Faucibus et molestie ac feugiat sed lectus vestibulum mattis ullamcorper. Sagittis id consectetur purus ut. Sagittis eu volutpat odio facilisis mauris sit amet massa vitae. Pellentesque pulvinar pellentesque habitant morbi tristique senectus. In massa tempor nec feugiat. Faucibus interdum posuere lorem ipsum. Scelerisque viverra mauris in aliquam. Feugiat in fermentum posuere urna nec tincidunt praesent semper feugiat. Consequat interdum varius sit amet mattis vulputate. Blandit turpis cursus in hac habitasse platea dictumst quisque sagittis. Dictum at tempor commodo ullamcorper a lacus vestibulum sed. Lacus sed viverra tellus in hac habitasse platea dictumst. Tellus pellentesque eu tincidunt tortor. Ridiculus mus mauris vitae ultricies leo integer. Varius sit amet mattis vulputate enim nulla. In egestas erat imperdiet sed euismod nisi.

```scala
 lazy val commonJavaSettings = commonSettings ++ Seq(
   version := dottyVersion,
   scalaVersion := referenceVersion,
   // Do not append Scala versions to the generated artifacts
   crossPaths := false,
   // Do not depend on the Scala library
   autoScalaLibrary := false,
   excludeFromIDE := true,
   disableDocSetting
 )

 lazy val commonDottySettings = commonSettings ++ Seq(
   // Manually set the standard library to use
   autoScalaLibrary := false,
   classpathOptions ~= (old =>
     old
       .withAutoBoot(false)      // no library on the compiler bootclasspath - we may need a more recent version
       .withFilterLibrary(false) // ...instead, we put it on the compiler classpath
   ),
 )

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
