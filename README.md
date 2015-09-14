java-hwp
========

This product has been developed with reference to the Hangul document file (.hwp) Hangul in public documents and computers.

Cogniti given a lot of help in the development Thank you for your friendship and group libhwp Google Group.

Java library to extract text from HWP files and the Java version of ruby-hwp. the logic of ruby-hwp most part, accept, and the character mapping of HWP 3.0 version uses the hnc2unicode.inc file to logic and mapping data of hnc2unicode.c of libghwp. Add to hnc2unicode.inc Some said the special character maps b.

The Compound File HWP 5.0 version of POIFS File System is processed using the Apache-POI.

How to use

File hwp = new File ("hangul.hwp"); // HWP files to extract the text

Writer writer = new StringWriter (); // Buffer to output the extracted text

HwpTextExtractor.extract (hwp, writer); // Extract text from files

String text = writer.toString (); // Extracted text
