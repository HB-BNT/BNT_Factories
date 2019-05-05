Readme
======
BNT\_Factories extends the CSPP\_Core package of the *CS++* project. 

It contains a derived classes of CSPP\_Factory.

Refer to https://git.gsi.de/EE-LV/CSPP/CSPP for *CS++* project overview, details and documentation.

LabVIEW 2018 is the currently used development environment.

Related documents and information
=================================
- README.md
- EUPL v.1.1 - Lizenz.pdf
- Contact: Holger.Brand@BrandNewTechnologies.de
- Download, bug reports... : http://github.com/HB-BNT/BNT_Factories
- Documentation:
  - Refer to package folder

GIT Submodules
==============
This package can be used as submodule.

- Packages\BNT_Factories

External Dependencies
---------------------
- CSPP\_Core: https://git.gsi.de/EE-LV/CSPP/CSPP_Core
- Blowfish Encryption Algorithm: 
  - https://www.labviewforum.de/Thread-Blowfish-6-0 included in distribution or
  - http://www.ni.com/example/28473/en/

Getting started:
=================================
- Add BNT_Factories.lvlib into your own LabVIEW project.
- Extract to C:\Program Files (x86)\National Instruments\LabVIEW 2018\user.lib\Blowfish6.0


BNT_BlowfishFactory
-------------------
- You need to convert your project specific ini-file using _ASCII to Blowfish Encrypted.vi_.
- You need to set the password in _BNT\_BlowfishFactories.lvlib:BNT\_BlowfishFactory.lvclass_ and connect this factory to "CSPP\_StartActor:Launch CSPP\_StartActor.vi_ in your _Main.vi_.

Lizenziert unter EUPL V. 1.1 
  
Author: Holger.Brand@BrandNewTechnologies.de

Copyright 2019  Brand New Technologies

Dr. Holger Brand, Asternweg 12a, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.