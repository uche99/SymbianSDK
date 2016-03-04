NG = N-Gage, NGQD = N-Gage QD


# Descriptions

* [NG Wikipedia article](https://en.wikipedia.org/wiki/N-Gage_(device))
* [NGQD Wikipedia article](https://en.wikipedia.org/wiki/N-Gage_QD)
* [NQD User manual](http://www.manualslib.com/manual/112327/Nokia-N-Gage-Qd.html?page=4#manual)
* [NQD service manual and schematics](http://www.cpkb.org/wiki/Nokia_N-Gage_QD_service_manual_and_schematics_download)

# CPU

* [ARM920T Technical Reference Manual](http://infocenter.arm.com/help/index.jsp?topic=/com.arm.doc.ddi0151c/I71066.html) 
* [ARMv4 Architecture Reference Manual](https://www.altera.com/content/dam/altera-www/global/en_US/pdfs/literature/third-party/archives/ddi0100e_arm_arm.pdf)

# SDK

A N-Gage SDK existed and even had multiple version but it was not obtainable without a contract with Nokia but the the reference and the install guide of the N-Gage sdk are available (see "Documentation"). The N-Gage being a part of the s60 phone series, there is a chance we could use / gain some information from the s60 SDK.


* [s60 SDK v5](http://www.mediafire.com/download/mbahmx9nyry45vj/S60_5th_SDK_ASP_v1.0.1.zip)
* [Archive of Nokia's Tools and SDKs](https://www.mediafire.com/folder/79jhy594xb3uk/Symbian_Development)


# Firmware

The version 4.03 is the most available version to download. Versions 4.10 and 4.11 also seems to exist but have problems ([source](http://my-symbian.com/forum/viewtopic.php?t=19466))

Here is a link of available downloads found from the net but nothing has been tested:

* [NG 4.03 Flash Files](http://www.freeflashfile.com/nokia.php?opt=bm9raWEvRENUNC9OR0FHRS5ORU0tNA%3D%3D)
* [NEM-4_0403_Ngage.exe](http://www.4shared.com/file/FGyn2kWL/NEM-4_0403_Ngage.html)
* [Collection of Nokia's firmware (seems dead)](http://forum.gsmhosting.com/vbb/6329670-post3.html)

# OS

While not the exact version that the NG ran and without every NG specific modules, we can still download the source from Symbian OS as it was in 2010-2011 (7 years after the NG)

* [Symbian-dump](https://sourceforge.net/projects/symbiandump/)


# Documentation

* [NQD service manual and schematics](http://www.cpkb.org/wiki/Nokia_N-Gage_QD_service_manual_and_schematics_download)
* [NG SDK Reference & Other technical references](https://techwriter79.wikispaces.com/Nokia)
    - [NG API Reference (all NG-specific headers)](https://techwriter79.wikispaces.com/file/view/Ngage_API_Reference.chm/555671371/Ngage_API_Reference.chm)
    - [NG Example Reference (headers only - source is available in the SDK)](https://techwriter79.wikispaces.com/file/view/Ngage_Examples.chm/555671383/Ngage_Examples.chm)
* [NG SDK install guide](https://techwriter79.wikispaces.com/file/view/NGage_SDK_2.1_Installation_Guide.pdf)
* [Archive of Symbian C++ docs](http://web.archive.org/web/20141028092534/http://developer.nokia.com/community/wiki/Symbian_C%2B%2B)
* [.sis file format documentation](http://www.thoukydides.webspace.virginmedia.com/sis.html)
* [Primer on reversing Symbian S60 Applications by Shub Nigurrath v14](https://mega.nz/#!pIYQxBLQ!dXoXBt2_kjmJ4RHmRDrSreZn9c1U3oTJ-WYbSDbKqu8)
* [E32Image file format (.app)](https://web.archive.org/web/20091213034509/http://wiki.forum.nokia.com/index.php/E32Image)
* [Symbian OS Internals: Real-time Kernel Programming](http://citeseerx.ist.psu.edu/viewdoc/download?rep=rep1&type=pdf&doi=10.1.1.168.3691)
* [Symbian OS Explained: Effective C++ Programming For Smartphones](http://g-02.ebooks-it.org/e-books/wiley/Wiley.Symbian.OS.Explained.Jan.2005.ISBN.0470021306.pdf?l=Sj-Kh7qEEUDqkpLqhiMbFQ)

# IDA
* [Import ids](https://mega.nz/#!EdRViIpR!a_b0y4lw2tufpvu6hDSahpqFXJDZ44E5kqam9AstNvA) (place in /IDA/ids/epoc6/arm/)
  - Generated from 3rd Edition Symbian S60 SDK (need N-Gage SDK for accurate generation)

# Tools

* [Sisexplorer, open and explore .sis files](http://www.symbian-toys.com/sisxplorer.aspx)

# Miscellaneous

* [[Ru] Install a game on a N-Gage](http://rutracker.org/forum/viewtopic.php?t=329313)
* [Create a sis app using python](http://www.mobilenin.com/pys60/info_standalone_application.htm)