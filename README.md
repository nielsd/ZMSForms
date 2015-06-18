# ZMSForms
Easy Formulator Forms for ZMS (the Zope based CMS)

*2015 by Niels Dettenbach <nd@syndicat.com> / Syndicat IT & Internet http://www.syndicat.com
GPLv2 licensed*

ZMSForms (aka KForms) allows end user compatible handling of HTML forms, contact forms including 
form logic in ZMS web sites. As a multi language "special object" it allows to place web forms everywhere in a 
ZMS site just by click, selecting from multiple form templates and changing any important parameters for typical
web forms.

By default any form input is - after vaildation - handled by email, but it allows easy integration of further logic or other 
applications / midleware too.

ZMSForms is delivered with a standard "contact form" (in german and english) plus some further examples 
from the alpinres.org project. 

Own form templates - including any validation logic - could very easily exported / imported / interchanged between 
ZMS instances / installations and hosts in a single file (XML based). The Formulator object allows very easy adaptions
of forms or even creating completely new ones from ground up by clicks.

One of the major features of ZMS is the OO "parent/child" portal setup allowing to manage multiple / many 
(more or less) similiar web sites from a single parent instance. ZMSForms allows to provide any Form module to 
any or just specific child sites here and central updates etc. too..

ZMS is a Zope based CMS ( http://www.zms-publishing.com )
The Zope framework is a Community Propject ( http://www.zope.org )
Formulator is a Zope Product ( http://infrae.com/products/formulator )


INSTALL
-------
As ZMS Administrator, import the spcial object and the language pack as usual.
In the ZMS ROOT (where the templates reside) import "ZMSForms.zexp" - the folder where the Form 
modules reside (incl. examples).


TODO
-----
 - further Documentation
 - more languages
 - free / complex form layout
 - auto PDF format conversion

CHANGES since KForms 1.0
---------------------------
- XHTML / CSS style / table free layout
- anti spam mechanism
- compatibility to ZMS >2.13
- easy installation / interchange of Forms / Form Modules
- multi language
- HTML/Text Emails
- send reciepts if configured
- languases added: german, english, french, italian, slovensko


CONTACT
--------
      Niels Dettenbach
      Mail: nd@syndicat.com
      WWW: http://www.syndicat.com

      Current project page: 
      https://github.com/nielsd/ZMSForms

Hope you enjoy it!


PRE-REQUISITES
--------------
- ZOPE
- ZMS
- Formulator

LICENSE
--------
GPL version 2
