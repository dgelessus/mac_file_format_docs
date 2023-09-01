# Mac File Format Docs

A collection of technical documentation and specifications about Apple- and Mac-related file formats, mainly from the classic Mac OS and early Mac OS X era.

If any links on this page are no longer functional, check if they have been archived by the [Internet Archive Wayback Machine](https://archive.org/web/), or using [archive.is](http://archive.is/) aka [archive.fo](https://archive.fo/).

## License

[!["Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

**Note:** The license only applies to the contents of this repository. All linked external websites and documents are subject to their own copyright notices and license terms.

## General information

These resources provide general documentation about the Mac, its internals, and development for the platform. They don't focus on any specific topic.

### Non-Mac-specific

These resources are not Mac-specific, but contain some Mac-related information.

* [Wikipedia](https://en.wikipedia.org/) has articles about many Mac-related topics. The articles themselves usually don't go into deep technical detail, but the references and external links are often worth looking at for more information.
* <a id="jstffp"></a>The [Just Solve the File Format Problem](http://fileformats.archiveteam.org/) wiki, run by [Archive Team](https://archiveteam.org/), provides information about various file formats. The name might sound like clickbait, but this is a decent site with useful information. As with Wikipedia, the articles often don't go into much detail, but the links are useful for further research.
* <a id="kaitai-struct"></a>The [Kaitai Struct format gallery](https://formats.kaitai.io/) is a collection of [Kaitai Struct](https://kaitai.io/) specifications for common file formats. The source code for all specs can be found in the [kaitai-io/kaitai_struct_formats](https://github.com/kaitai-io/kaitai_struct_formats) GitHub repo. These specs can be compiled to many popular programming languages to allow parsing files in the specified format.

* The [Internet Archive (archive.org)](https://archive.org/) has some Mac-related literature, documents and software. Aside from the general search function, the following collections are relevant in particular:

	* [Folkscanomy: Macintosh Books](https://archive.org/details/macbooks)
	* [The Software Library: Apple Computer](https://archive.org/details/softwarelibrary_apple) (this collection focuses mainly on the non-Macintosh Apple computers)
	* [Software Library: Macintosh](https://archive.org/details/softwarelibrary_mac)

* [bitsavers.org](http://bitsavers.org/) is an archive of documents (and some software) related to technology and computing. The site has no built-in search function, but external search engines can be used. It is also mirrored to archive.org (at least partially), so it can be searched using their search function. The site is organized by topic, so a text search often isn't necessary. The following directories are relevant in particular:

	* [/bits/Apple/](http://bitsavers.org/bits/Apple/)
	* [/components/ibm/powerpc/](http://bitsavers.org/components/ibm/powerpc/)
	* [/components/motorola/](http://bitsavers.org/components/motorola/)
	* [/pdf/apple/](http://bitsavers.org/pdf/apple/)

### Mac-specific

These resources are specifically about Apple and the Mac.

* <a id="apple-developer-download"></a>[Apple's developer download section](https://developer.apple.com/download/more/) provides downloads for Xcode and other Mac OS X/macOS developer tools. The earliest downloads are from the Mac OS X Panther (10.3) era. Accessing this page requires an Apple ID with a developer program membership (the free membership is sufficient).

* <a id="apple-documentation-archive"></a>[Apple's developer documentation](https://developer.apple.com/documentation/) is the official source of developer information for Apple's platforms. The main section of the website only covers current system versions, but older information can be found in the [documentation archive](https://developer.apple.com/library/archive/navigation/). Unfortunately, Apple sometimes arbitrarily removes older documents from the archive. It's not clear how Apple decides what to remove - it's not purely based on age, as the oldest available documents (as of October 2019) are tech notes from 1985. This means that some older documentation can only be found in old copies of the website, such as the following:

	* The [Wayback Machine](https://web.archive.org/) has saved almost all parts of the site at some point. The URLs of the documentation and archive have changed in the past - if the Wayback Machine doesn't have a URL saved, it may help to search for the same URL with a different prefix. The following prefixes were used in the past (ordered from newest to oldest):
	
		* [https://developer.apple.com/library/archive/](https://web.archive.org/web/*/https://developer.apple.com/library/archive/) (legacy)
		* [https://developer.apple.com/library/mac/](https://web.archive.org/web/*/https://developer.apple.com/library/mac/) (non-legacy), [https://developer.apple.com/legacy/library/](https://web.archive.org/web/*/https://developer.apple.com/legacy/library/) (legacy)
		* [https://developer.apple.com/mac/library/](https://web.archive.org/web/*/https://developer.apple.com/mac/library/) (non-legacy), [https://developer.apple.com/legacy/mac/library/](https://web.archive.org/web/*/https://developer.apple.com/legacy/mac/library/) (legacy)
	
	* A copy dated August 2010 can be found [on the Internet Archive](https://archive.org/details/ftpsites_developer.apple.com) and [on macintosharchive.org's mirror of Max1zzz's server](http://mirror.macintosharchive.org/max1zzz.co.uk/++Uploads%20%5bUL%5d/Barracuda/FTP%20mirrors/ftpsites_developer.apple.com/).
	* oldschooldaw.com has [a mirror](http://adcmirror.oldschooldaw.com/) from October 2006. This mirror has itself [been mirrored](http://mirror.macintosharchive.org/developer.apple.com/) by macintosharchive.org.

* Apple's Technical Notes provided developer documentation for classic Mac hardware and software. Some of them can still be found in Apple's documentation archive, but many of them have been removed. Mirrors of the technical notes can be found online:

	* fenestrated.net has [a mirror of the technical notes](https://www.fenestrated.net/mirrors/Apple%20Technotes%20(As%20of%202002)/) from 2002.
	* A collection of developer notes can be found [on the Internet Archive](https://archive.org/details/nonmm-apple-dev-notes) and [on macintosharchive.org's mirror of Max1zzz's server](http://mirror.macintosharchive.org/max1zzz.co.uk/++Uploads%20%5bUL%5d/Barracuda/nonmm-apple-dev-notes/).

* <a id="apple-support-area"></a>The [Apple Support Area on download.info.apple.com](http://download.info.apple.com/Apple_Support_Area/), Apple's download section for pre-Mac OS X systems (and some early Mac OS X-related files). The files under this directory tree can still be downloaded from Apple, although the server no longer provides directory listings. The contents of this server are also widely mirrored:

	* The [Wayback Machine](https://web.archive.org/web/*/http://download.info.apple.com/Apple_Support_Area/) contains a likely complete copy of the directory listings and files.
	* The Internet Archive has [a copy](https://archive.org/details/download.info.apple.com.2012.11), and [another one](https://archive.org/details/ftpsites_download.info.apple.com).
	* Max1zzz's server has [a copy of the Apple_Software_Updates subdirectory](http://asa.max1zzz.co.uk/).
	* macintosharchive.org has [a copy](http://mirror.macintosharchive.org/download.info.apple.com/).
	* fenestrated.net has [a copy](https://www.fenestrated.net/mirrors/Apple_Support_Area/), which can also be found [in macintosharchive.org's mirror of Max1zzz's server](http://mirror.macintosharchive.org/max1zzz.co.uk/++Uploads%20%5bUL%5d/Barracuda/FTP%20mirrors/www.fenestrated.net/mirrors/Apple_Support_Area/).

* <a id="apple-ftp"></a>ftp.apple.com, Apple's FTP server. Like many old FTP servers, it is no longer online. Some of its content is available from download.info.apple.com (see above). There are also some mirrors of the FTP server:

	* A mirror claiming to be from November 2018 (date likely incorrect) can be found [on the Internet Archive](https://archive.org/details/Apple_Computer_FTP_Mirror_2018-11) and [on macintosharchive.org's mirror of Max1zzz's server](http://mirror.macintosharchive.org/max1zzz.co.uk/++Uploads%20%5bUL%5d/Barracuda/FTP%20mirrors/Apple%20FTP%20mirror/).
	* staticky.com has a [partial mirror of the developer subdirectory](http://staticky.com/mirrors/ftp.apple.com/). This mirror is incomplete - apparently the server was mirrored with a low directory depth limit, so the contents of deeply nested directories were not mirrored.

* [Macintosh Garden](https://macintoshgarden.org/) and [Macintosh Repository](https://www.macintoshrepository.org/) are archives of classic Mac (and early Mac OS X) freeware, abandonware and related documentation. They are useful places to find system files and developer tools.

	* The Internet Archive has [a mirror of Macintosh Garden's files](https://archive.org/details/Macintosh_Garden_Collection) from 2018.

* macintosharchive.org hosts [a collection of mirrors](http://mirror.macintosharchive.org/) of Mac-related websites.
* [Max1zzz's server](http://max1zzz.co.uk) was a collection of Mac-related files and mirrors, but as of April 2019 it is no longer online. [A complete mirror](http://mirror.macintosharchive.org/max1zzz.co.uk/) can be found on macintosharchive.org.
* [VintageApple.org](https://vintageapple.org/) is a collection of early Apple and Mac documents and a couple of mirrors.
* https://www.mothersruin.com/software/Archaeology/reverse/

#### Inside Macintosh

The Inside Macintosh book series are Apple's official reference material for the classic Macintosh platform. Over time, they have gone through many revisions and updates, and their structure has been changed multiple times.

The Gryphel project (best known for the Mini vMac emulator) has [a list of physical book releases](https://www.gryphel.com/c/books/appledev.html) of Inside Macintosh (and other Apple developer documentation), including ISBNs, publishers, dates, and Amazon links.

The following is a (likely incomplete) list of the major revisions of Inside Macintosh and where they can be obtained online.

* The earliest revisions consisted of two volumes, each a three-ring binder containing photocopied pages. The chapters were referred to as individual "manuals" and were essentially standalone - each one had its own title page, TOC, glossary, and page numbers. Various parts were still missing or not yet finalized, and updated pages were distributed regularly as part of the [Macintosh Software Supplement](https://macgui.com/news/article.php?t=447).

	* bitsavers.org has scanned and OCRed PDFs of a late (November 1984) revision: [Volume I](http://bitsavers.org/pdf/apple/mac/Inside_Macintosh_Vol_1_1984.pdf), [Volume II](http://bitsavers.org/pdf/apple/mac/Inside_Macintosh_Vol_2_1984.pdf).

* The Promotional Edition, released in early 1985, consisted of a single book (it was nicknamed the "phonebook" edition because of its paper quality). Although it was physically a single book, the contents were still structured into standalone "manuals" like in the ring binder version, and some parts were still missing or not finalized.

	* bitsavers.org has [a scanned and OCRed PDF](http://bitsavers.org/pdf/apple/mac/Inside_Macintosh_Promotional_Edition_1985.pdf).

* The published 1985 revision consisted of three volumes, available as three paperback books or a single hardcover book. They contained the finalized contents of the previous revisions, which documented the Macintosh 128k, Macintosh 512k, and Macintosh XL. Unlike the previous revisions, each volume had continuous page numbers and a full TOC and index, and volume III contained a complete glossary.

	* pagetable.com has a [blog post](http://www.pagetable.com/?p=50) with [a scanned and OCRed PDF of the three paperback volumes](http://www.weihenstephan.org/~michaste/pagetable/mac/Inside_Macintosh.pdf).

* Additional volumes were published later to document newer Macintosh models. These served as incremental additions and did not fully supersede or replace any of the previous volumes.

	* Volume IV was published in 1986 and documented the Macintosh Plus and Macintosh 512k Enhanced.
	* Volume V was published in 1986 and documented the Macintosh II and Macintosh SE.
	* Volume VI was published in 1991 and documented System 7.0.
	* VintageApple.org has [scanned and OCRed PDFs of Volumes I through VI](https://vintageapple.org/inside_o/).

* After 1991, Inside Macintosh was restructured into over 20 volumes organized by topic, rather than chronologically by Macintosh model. These were published as books starting in 1992, and later also on CDs and online.

	* VintageApple.org has [rendered (not scanned) PDFs of 26 volumes and 7 X-Ref volumes](https://vintageapple.org/inside_r/).
	
		* The Communications Toolbox and QuickDraw GX Programmers' Overview volumes appear to be missing.
	
	* Many volumes are still available in [Apple's legacy developer documentation archive](#apple-documentation-archive), in HTML and rendered (not scanned) PDF formats:
	
		* Two volumes appear on the website under Inside Macintosh, even though other sources don't consider them part of the Inside Macintosh series:
		
			* [Advanced Color Imaging on the Mac OS (HTML)](https://developer.apple.com/library/archive/documentation/mac/ACI/ACI-2.html) (November 1996)
			* [Advanced Color Imaging Reference (HTML)](https://developer.apple.com/library/archive/documentation/mac/ACIReference/ACIReference-2.html) (November 1996)
		
		* [Devices (HTML)](https://developer.apple.com/library/archive/documentation/mac/Devices/Devices-2.html) (July 1996), [Devices (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Devices/pdf.html) (1994)
		* [Files (HTML)](https://developer.apple.com/library/archive/documentation/mac/Files/Files-2.html) (July 1996), [Files (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Files/pdf.html) (1992)
		* [Imaging with QuickDraw (HTML)](https://developer.apple.com/library/archive/documentation/mac/QuickDraw/QuickDraw-2.html) (July 1996), [Imaging with QuickDraw (single PDF)](https://developer.apple.com/library/archive/documentation/mac/pdf/ImagingWithQuickDraw.pdf) (1994)
		* [Interapplication Communication (HTML)](https://developer.apple.com/library/archive/documentation/mac/IAC/IAC-2.html) (July 1996), [Interapplication Communication (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Interapplication_Communication/pdf.html) (1993)
		* [Macintosh Toolbox Essentials (HTML)](https://developer.apple.com/library/archive/documentation/mac/Toolbox/Toolbox-2.html) (July 1996), [Macintosh Toolbox Essentials (single PDF)](https://developer.apple.com/library/archive/documentation/mac/pdf/MacintoshToolboxEssentials.pdf) (1992)
		* [Memory (HTML)](https://developer.apple.com/library/archive/documentation/mac/Memory/Memory-2.html) (July 1996), [Memory (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Memory/pdf.html) (1992)
		* [More Macintosh Toolbox (HTML)](https://developer.apple.com/library/archive/documentation/mac/MoreToolbox/MoreToolbox-2.html) (July 1996), [More Macintosh Toolbox (single PDF)](https://developer.apple.com/library/archive/documentation/mac/pdf/MoreMacintoshToolbox.pdf) (1993)
		* [Networking (HTML)](https://developer.apple.com/library/archive/documentation/mac/Networking/Networking-2.html) (July 1996), [Networking (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Networking/pdf.html) (1994)
		* [Operating System Utilities (HTML)](https://developer.apple.com/library/archive/documentation/mac/OSUtilities/OSUtilities-2.html) (July 1996), [Operating System Utilities (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Operating_System_Utilities/pdf.html) (1994)
		* [PowerPC Numerics (HTML)](https://developer.apple.com/library/archive/documentation/mac/PPCNumerics/PPCNumerics-2.html) (July 1996), [PowerPC Numerics (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/PPC_Numerics.sit.hqx) (1994)
		* [PowerPC System Software (HTML)](https://developer.apple.com/library/archive/documentation/mac/PPCSoftware/PPCSoftware-2.html) (July 1996), [PowerPC System Software (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/PPC_System_Software.sit.hqx) (1994)
		* [Processes (HTML)](https://developer.apple.com/library/archive/documentation/mac/Processes/Processes-2.html) (June 1996), [Processes (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Processes/pdf.html) (1992)
		* [Sound (HTML)](https://developer.apple.com/library/archive/documentation/mac/Sound/Sound-2.html) (July 1996), [Sound (chapter PDFs)](https://developer.apple.com/library/archive/documentation/mac/pdf/Sound/pdf.html) (1994)
		* [Text (HTML)](https://developer.apple.com/library/archive/documentation/mac/Text/Text-2.html) (July 1996), [Text (single PDF)](https://developer.apple.com/library/archive/documentation/mac/pdf/Text.pdf) (1993)
		* The two AOCE volumes, Communications Toolbox, Human Interface Guidelines, Overview, seven QuickDraw GX volumes, two QuickTime volumes, and X-Ref are missing.

## File type and creator codes (file signatures)

* The chapter "The Finder Interface" in the [Inside Macintosh](#inside-macintosh) series explains the basic concepts and lists a few standard/system file type codes. This chapter is found in Volume III of the original Inside Macintosh revisions, and in the "Macintosh Toolbox Essentials" volume of the restructured revisions.
* Apple previously provided a registration service for creator codes to prevent conflicting uses of the same creator codes. This included a lookup form for checking if a creator code is already in use, but there was no public list of all creator codes.
	* An [early 2000s version of the service](https://web.archive.org/web/20031204220705/http://developer.apple.com/dev/cftype/) also had [a FAQ about creator code registration](https://web.archive.org/web/20031206002820/http://developer.apple.com/dev/cftype/faq.html).
	* The last version of the service was found at https://developer.apple.com/datatype/ until 2009 or so (based on the Wayback Machine history). Afterwards, that URL redirected to [Apple's documentation for Uniform Type Identifiers (UTIs)](https://developer.apple.com/library/archive/documentation/FileManagement/Conceptual/understanding_utis/understand_utis_intro/understand_utis_intro.html), which are the modern replacement for type and creator codes.
* The Type/Creator Database (TCDB/TCDBx) is exactly what it sounds like. Notably, it's a downloadable application, not an online service.
	* It was previously a paid product, but [the current homepage at lacikam.co.il](https://lacikam.co.il/tcdb/) offers a [free download of the full data set](https://lacikam.co.il/tcdb/download/TCDBdata.zip).
	* The [former homepage at homepage.mac.com/tcdb/](https://web.archive.org/web/20100106142542/http://homepage.mac.com/tcdb/) is no longer up, but can be found in the Wayback Machine.
	* Various versions of the downloads are [mirrored on Macintosh Garden](https://macintoshgarden.org/apps/typecreator-database).
* Indiana University has [a very short explanation](https://kb.iu.edu/d/aemh) of type/creator codes.
* macdisk.com has an explanation page "[Signatures of Macintosh Files](https://www.macdisk.com/macsigen.php)", including a list of some common type and creator codes.
* Zeus Productions has [a "tech note"](http://www.zeusprod.com/technote/filetype.html) explaining how to use type/creator codes in Macromedia Director (I think). It also explains some general concepts and lists common and Director-specific type/creator codes.
* revolution.byu.edu had a help article "[Mac Creator Signature and File Types in Revolution/LiveCode](https://web.archive.org/web/20171118233752/revolution.byu.edu/helps/file-creatorcodes.php)", which also gives a short general explanation, a list of a few common type and creator codes, and some related links.
* A [2005 post by Henning Ramm](https://mail.python.org/pipermail/pythonmac-sig/2005-February/013028.html) on the Pythonmac-SIG mailing list gives some mappings from type/creator codes to file extensions (and vice versa) and short descriptions.

## Resource forks

* The chapter "Resource Manager" in the [Inside Macintosh](#inside-macintosh) series. This chapter is found in Volume I of the original Inside Macintosh revisions, and in the "More Macintosh Toolbox" volume of the restructured revisions.
* Wikipedia's [resource fork](https://en.wikipedia.org/wiki/Resource_fork) article.
* The [Resource Fork](http://fileformats.archiveteam.org/wiki/Resource_Fork) article on the [JSTFFP](#jstffp) wiki.
* The [KSFL](https://github.com/kreativekorp/ksfl) library (and [its wiki](https://github.com/kreativekorp/ksfl/wiki/Macintosh-Resource-File-Format)), written in Java, which supports reading and writing resource files.
* Alysis Software Corporation's article on resource compression (found on [the company's website](http://www.alysis.us/arctechnology.htm) and in [MacTech Magazine's online archive](http://preserve.mactech.com/articles/mactech/Vol.09/09.01/ResCompression/index.html)) has some information on the structure of certain kinds of compressed resources.
* Apple's macOS SDK, which is distributed with Xcode. The latest version of Xcode is available for free from the Mac App Store. Current and previous versions can be downloaded from [Apple's developer download section](#apple-developer-download).
* Apple's MPW (Macintosh Programmer's Workshop) and related developer tools and their documentation. These were previously available from [Apple's FTP server](#apple-ftp).
* whitefiles.org has a "[Resources](https://whitefiles.org/mac/pgs/t02.htm)" page explaining the basics of ResEdit and common system resource types.

## AFP (Apple Filing Protocol)

* Wikipedia's [AFP article](https://en.wikipedia.org/wiki/Apple_Filing_Protocol).
* The [AFP programming guide](https://developer.apple.com/library/archive/documentation/Networking/Conceptual/AFP/Introduction/Introduction.html) and [AFP reference](https://web.archive.org/web/20130906023421/https://developer.apple.com/library/mac/documentation/Networking/Reference/AFP_Reference/Reference/reference.html) from [Apple's developer documentation](#apple-documentation-archive).

### Windows NT Services for Macintosh

* A [microsoft.public.windowsnt.mac Usenet discussion](https://groups.google.com/d/topic/microsoft.public.windowsnt.mac/PTisz9EZWQg/discussion) (individual raw messages: [question](https://groups.google.com/forum/message/raw?msg=microsoft.public.windowsnt.mac/PTisz9EZWQg/nV__6uMIPawJ), [answer](https://groups.google.com/forum/message/raw?msg=microsoft.public.windowsnt.mac/PTisz9EZWQg/JaWO4vUM75oJ)) about how AFP file information and resource forks are stored on Windows NTFS volumes. (TLDR: alternate data streams named AFP_AfpInfo and AFP_Resource.)

## AppleSingle and AppleDouble

* The articles on the [JSTFFP](#jstffp) wiki about [AppleSingle](http://fileformats.archiveteam.org/wiki/AppleSingle) and [AppleDouble](http://fileformats.archiveteam.org/wiki/AppleDouble).
* The [Kaitai Struct](#kaitai-struct) spec `filesystem/apple_single_double`, as found [on formats.kaitai.io](https://formats.kaitai.io/apple_single_double/index.html) and [in the kaitai_struct_formats repo](https://github.com/kaitai-io/kaitai_struct_formats/blob/master/filesystem/apple_single_double.ksy).

* Apple's Apple II File Type Notes for AppleSingle (E0 0001) and AppleDouble (E0 0002 and E0 0003), which document version 1 of the format, with a short note about version 2. These notes can be found in many places online:

	* On nulib.com, in plain text format: [AppleSingle](https://nulib.com/library/FTN.e00001.htm), [AppleDouble](https://nulib.com/library/FTN.e000023.htm) (mirrored on ee.columbia.edu: [AppleDouble](https://www.ee.columbia.edu/~dpwe/resources/FTN.e000023.htm))
	* On 1000bit.it, in formatted HTML format: [AppleSingle](https://www.1000bit.it/support/manuali/apple/technotes/ftyp/ftn.e0.0001.html), [AppleDouble](https://www.1000bit.it/support/manuali/apple/technotes/ftyp/ftn.e0.0002.3.html)
	* On apple2online.com, in rendered PDF format: [AppleSingle](https://www.apple2online.com/web_documents/ft_e0.0001_applesingle.pdf), [AppleDouble](https://www.apple2online.com/web_documents/ft_e0.0002.3_appledouble.pdf)

* Apple's A/UX Toolbox Macintosh ROM Interface documentation, section 6 "File Systems and File Formats", subsection "AppleSingle and AppleDouble format internals", which documents version 1 of the format.

	* bitsavers.org has [a scanned and OCRed PDF of the entire document](http://bitsavers.org/pdf/apple/mac/a_ux/aux_2.0/030-0787-A_AUX_Toolbox_Macintosh_ROM_Interface_1990.pdf). In this version, the relevant pages are 6-15 through 6-20 (real page numbers 126 through 131).
	* kaiser-edv.de had [a scanned PDF of the relevant pages](https://web.archive.org/web/20160325000219/http://kaiser-edv.de/documents/AppleSingle_AppleDouble_v1.pdf) (website gone, link via Wayback Machine) from a slightly different edition.

* Apple's AppleSingle/AppleDouble Formats for Foreign Files Developer's Note, from 1990, which documents version 2 of the format. A rendered PDF version is available [from nulib.com](https://nulib.com/library/AppleSingle_AppleDouble.pdf) and [from kaiser-edv.de](https://web.archive.org/web/20180311140826/http://kaiser-edv.de/documents/AppleSingle_AppleDouble.pdf) (website gone, link via Wayback Machine).

* [RFC 1740 -  MIME Encapsulation of Macintosh files - MacMIME](https://tools.ietf.org/html/rfc1740), from 1994, describes a later version of the format. (It appears to be equivalent to version 2 described in the previous developer's note.)

* A number of GitHub projects work with AppleSingle/AppleDouble files in some way and allow reading the format in different languages. In no particular order:

	* https://github.com/AppleCommander/applesingle
	* https://github.com/fthain/applesingle
	* https://github.com/robzed/AppleSingle_Decoder
	* https://github.com/gitpan/Mac-AppleSingleDouble
	* https://github.com/marcust/AppleSingleReader
	* https://github.com/ksherlock/dot_clean
	* https://github.com/rolftimmermans/node-xattr-file
	* https://github.com/MacPaw/XADMaster/blob/master/XADAppleDouble.m
	* https://github.com/MacPaw/XADMaster/blob/master/XADAppleSingleParser.m
	* https://github.com/ParksProjets/Maconv

## QTR (QuickTime RezWack)

The QTR (QuickTime RezWack) format was used to add Mac-style resources to Windows files. It was used as part of QTML, the QuickTime Media Layer, which was effectively a partial port of the Macintosh Toolbox and Mac OS to Windows, to allow writing cross-platform QuickTime code that could be used with both Mac and Windows versions of QuickTime.

* Two articles from MacTech's online archive: one [about QuickTime for Windows and QTML development in general](http://preserve.mactech.com/articles/mactech/Vol.17/17.01/2001ASpaceOdyssey/index.html), and another [specifically about using QTR-based resources](http://preserve.mactech.com/articles/mactech/Vol.18/18.10/HumanResources/index.html).
* The QuickTime 7.3 SDK for Windows. It contains Windows versions of the DeRez, Rez, RezDet, and RezWack tools that use the QTR format, instead of normal resource forks like their Mac versions.

	* It can be officially downladed from [Apple's developer download section](#apple-developer-download). The file you download there is:
	
		* a Zip archive called quicktimesdk.zip (SHA256 [31ffc087e03a68585c7b67c7986e80eeb6440ac7fdb410a381e9b9da9b561d6d](https://www.virustotal.com/gui/file/31ffc087e03a68585c7b67c7986e80eeb6440ac7fdb410a381e9b9da9b561d6d/detection)), containing...
		* a self-extracting cabinet EXE called QuickTimeSDK.exe (SHA256 [fea9102899b6f6a1b20f1a1d1d656d28ffe32b99afb95c826548c0fef1d42bb1](https://www.virustotal.com/gui/file/fea9102899b6f6a1b20f1a1d1d656d28ffe32b99afb95c826548c0fef1d42bb1/details)), containing...
		* an MSI installer called QuickTimeSDK.msi (SHA256 [40fb26259e60bd1711bd6845223392381b973a50d76ac231283bf603a2b4aff1](https://www.virustotal.com/gui/file/40fb26259e60bd1711bd6845223392381b973a50d76ac231283bf603a2b4aff1/detection)), containing the actual files.
	
	* The SDK can also be obtained elsewhere, in which case you might find it in any of the three formats listed above. If the file you downloaded matches any of the above hashes, you can be sure that it's the original unmodified SDK.
	
		* For example, the MSI version can be found in [a random GitHub repo](https://github.com/zhaozhongshu/quicktime-sdk-7.3-for-windows/blob/c174718dbea7f909c3666411c4952c9efd3372a9/QuickTimeSDK.msi).

## Classic Mac OS installer tomes

* https://github.com/kainjow/TomeViewerX
* https://github.com/MacPaw/XADMaster/issues/71

## Disk images

* The Mac OS X/macOS hdiutil(1) man page. Although naturally it focuses on how to work with disk images and doesn't specify any data formats, it does document lots of random technical details. In particular:
	* Under `hdiutil convert`is a list of basically all disk image formats and variants that Apple has ever supported.
	* The "compatibility", "history", and "what's new" sections give a pretty complete history of these disk image formats/variants and which system versions support them (or don't).
	* Some older info has been removed from the man page since macOS 11, which removed support for most Classic Mac OS disk image formats.
* Wikipedia's [Apple Disk Image](https://en.wikipedia.org/wiki/Apple_Disk_Image) article has some general information, but also documents the basic data structures of UDIF disk images.
* macdisk.com also documents [the basic data structures of UDIF disk images](https://www.macdisk.com/dmgen.php).
* NewOSXBook.com has a page "[Demystifying the DMG File Format](https://newosxbook.com/DMG.html)", which documents the main UDIF metadata structures.
* https://www.mothersruin.com/software/Archaeology/reverse/udif.html

## HFS+ file system compression

* A Macworld Mac OS X Hints [page about HFS+ compression in Mac OS X 10.6](https://web.archive.org/web/20220407045715/http://hints.macworld.com/article.php?story=20090902223042255). The comments discuss additional tools for examining de-/compressing files compressed with HFS+ compression.
	* One such tool, afsctool, has been developed by brkirch, the author of the above page. [brkirch's afsctool homepage](https://brkirch.wordpress.com/afsctool/) still exists (as of 2023-08), but the Google Drive download link isn't publicly accessible anymore. However, a few updated/extended versions of the afsctool source code can be found on GitHub:
		* https://github.com/jrk/afsctool - archived since 2018-01-21
		* https://github.com/RJVB/afsctool - still updated as of 2023 and supports newer macOS versions and compression algorithms like LZVN and LZFSE

## Apple Data Compression (ADC)

* macdisk.com documents [the ADC compression algorithm](https://www.macdisk.com/dmgen.php).
* [node-apple-data-compression](https://github.com/jhermsmeier/node-apple-data-compression) implements ADC decompression as a Node.js library.

## Apple Archives (.aar, .aea, .yaa)

* https://developer.apple.com/documentation/applearchive?language=objc
* https://developer.apple.com/forums/thread/133985
* https://wwws.nightwatchcybersecurity.com/2020/06/14/yaa-an-obscure-macos-compressed-file-format/
* https://eclecticlight.co/2022/05/10/inside-apple-archive-more-than-a-compression-format/
* https://eclecticlight.co/2020/11/24/compress-and-decompress-files-using-applearchive/
* https://github.com/aonez/Keka/issues/829

## UIKit NIB archives (.nib files with NIBArchive signature)

* https://www.mothersruin.com/software/Archaeology/reverse/uinib.html
* https://github.com/JustHexData/nibarchive
