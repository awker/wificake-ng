**WiFiCake-NG**  
Perl::TK-based GUI for Aircrack-NG (Arircrack-ng.org), which includes wardriving reporting, WardriveSQL Dashboard (WeakNetLabs), Catchme-NG (WeakNetLabs), WiFiZap (WeakNetLabs) and more.

Version 1.7:
WiFiCake-NG\_v1.7.tar.gz<br />
New additions:<br />
1. PDF creation<br />
2. Smart mass deauthentication<br />
3. Signals window<br />
4. OUI check and logos in Signals WIndow<br />
5. OUI Logos in PDF<br />
6. Fixed Clients issue in PDF generation<br />
7. Channel locking and BSSID Locking onto target AP<br />
8. Automatic Channel retrieval, if not specified.<br />
9. Better support for rt73 && rt73USB drivers<br />
10. Cursor logos for de-auth, and refresh<br />
11. general clean up of code.<br />

<a href='http://www.youtube.com/watch?feature=player_embedded&v=oBHKKQNG5PM' target='_blank'><img src='http://img.youtube.com/vi/oBHKKQNG5PM/0.jpg' width='425' height=344 /></a>

### Dependencies ###
Perl5+
Perl-Tk; (Perl::Tk or just Tk)<br />
PDF::API2; (PDF creation)<br />
Tk::Pane; (Layout and Design)<br />
Cwd; (To read / write files from current working directory)<br />
Path::Entry; (TAB Auto Completion)<br />
Notebook; (Layout and Design)
Aircrack-NG Suite; (Sniffing, Packet Injection)<br />
Pyrit; (cracking WPA/WPA2)<br />
MySQL (server and client);<br />
sox; (play sounds)

### Manual ###
<a href='http://weaknetlabs.com/weaknet/download/wificake/wificake.pdf'><img src='http://weaknetlabs.com/weaknet/download/wificake/pdf.png' /></a>