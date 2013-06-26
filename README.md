TestJOGL
========

Minimal multiplatform demo for JOGL 2

BUILD 
	mvn package

RUN DEFAULT

	java -jar target/TestJOGL-1.0-SNAPSHOT.jar

RUN EACH EXAMPLE

	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.TestJOGL
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe02Basic2D
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe03Color
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe04Rotation
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe05Shape3D
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe06Texture
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe07TextureFilterLightKey
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe08Blending
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Nehe08Blending_FullScreen
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Setup_Applet
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Setup_GLCanvas
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Setup_GLCanvasFullScreen
	java -cp target/TestJOGL-1.0-SNAPSHOT.jar  com.xpressosystems.testjogl.JOGL2Setup_GLJPanel
