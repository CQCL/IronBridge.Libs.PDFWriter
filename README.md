# IronBridge.Libs.PDFWriter
3rd Party PDFWriter library used by RestServerCpp for PDF watermarking service


### Build and install PDFWriter library

```
md build
cd build
cmake .. && make && sudo make install
```

The resultant libraries are installed into a shared locations...
* Includes:
  * /usr/local/include/FreeType/
  * /usr/local/include/LibAesgm/
  * /usr/local/include/LibJpeg/
  * /usr/local/include/LibPng/
  * /usr/local/include/LibTiff/
  * /usr/local/include/PDFWriter/
  * /usr/local/include/ZLib/
* Libraries:
  * /usr/local/lib/libFreeType.a
  * /usr/local/lib/libLibAesgm.a
  * /usr/local/lib/libLibJpeg.a
  * /usr/local/lib/libLibPng.a
  * /usr/local/lib/libLibTiff.a
  * /usr/local/lib/libPDFWriter.a
  * /usr/local/lib/libZlib.a
