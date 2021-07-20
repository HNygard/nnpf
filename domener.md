NNPF sine domener (kilde: norid.no, 2021-07-20)

	970014179
	NORSK NARKOTIKAPOLITIFORENING
	Subscribes on 13 domain names registered on 1 registrars

	Via UNIWEB.NO AS
		brydeg.no
		motgift.no
		narkotika.no
		narkotikainfo.no
		narkotikainformasjon.no
		narkotikakurs.no
		narkotikapolitiforening.no
		narkotikapolitiforeningen.no
		nnpf.no
		norsk-narkotikapolitiforening.no
		norsknarkotikapolitiforening.no
		rusreformen.no
		tegnogsymptomer.no


Nedlastinger:

	wget --recursive --force-directories --timestamping -e robots=off https://nnpf.no

	wget --recursive --force-directories -e robots=off "https://nnpf.portal.styreweb.com/arrangement/Register?ID=37807-BABD"

	wget --recursive --force-directories -e robots=off "https://nnpf.portal.styreweb.com/api/listattachmentpublic/1331501/1790941/Personvernerkl%C3%A6ring.pdf"

---

	wget --recursive --force-directories --timestamping -e robots=off https://brydeg.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off http://brydeg.no
		=> 301 Moved Permanently, Location: https://nnpf.no/brydeg/
	wget --recursive --force-directories --timestamping -e robots=off https://motgift.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off http://motgift.no
		=> 301 Moved Permanently, Location: https://nnpf.no/motgift/
	wget --recursive --force-directories --timestamping -e robots=off https://narkotika.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off http://narkotika.no
		=> 301 Moved Permanently, Location: https://nnpf.no/
	wget --recursive --force-directories --timestamping -e robots=off https://narkotikainfo.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off https://narkotikainformasjon.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off https://narkotikakurs.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off https://narkotikapolitiforening.no
		=> SSL error
	wget --recursive --force-directories --timestamping -e robots=off https://narkotikapolitiforeningen.no
		=> SSL error
	wget --recursive --force-directories --timestamping -e robots=off https://norsk-narkotikapolitiforening.no
		=> SSL error
	wget --recursive --force-directories --timestamping -e robots=off https://norsknarkotikapolitiforening.no
		=> SSL error
	wget --recursive --force-directories --timestamping -e robots=off https://rusreformen.no
		=> Failed
	wget --recursive --force-directories --timestamping -e robots=off https://tegnogsymptomer.no
		=> Failed

	wget --recursive --force-directories --timestamping -e robots=off http://narkotikainfo.no
		=> 301 Moved Permanently, Location: http://Www.nnpf.no
	wget --recursive --force-directories --timestamping -e robots=off http://narkotikainformasjon.no
		=> 301 Moved Permanently, Location: http://Www.nnpf.no 
	wget --recursive --force-directories --timestamping -e robots=off http://narkotikakurs.no
		=> 301 Moved Permanently, Location: https://nnpf.no/kurs/
	wget --recursive --force-directories --timestamping -e robots=off http://narkotikapolitiforening.no
		=> 302 Moved Temporarily, Location: https://parked.uniweb.no
	wget --recursive --force-directories --timestamping -e robots=off http://narkotikapolitiforeningen.no
		=> 302 Moved Temporarily, Location: https://parked.uniweb.no
	wget --recursive --force-directories --timestamping -e robots=off http://norsk-narkotikapolitiforening.no
		=> 302 Moved Temporarily, Location: https://parked.uniweb.no
	wget --recursive --force-directories --timestamping -e robots=off http://norsknarkotikapolitiforening.no
		=> 302 Moved Temporarily, Location: https://parked.uniweb.no
	wget --recursive --force-directories --timestamping -e robots=off http://rusreformen.no
		=> 200 OK med frames

	wget --recursive --force-directories --timestamping -e robots=off http://tegnogsymptomer.no
		=> 301 Moved Permanently, Location: https://nnpf.no/kurs/


----

Domener med mail hos Google:
- nnpf.no
- brydeg.no
- motgift.no

Domener med mail hos mx01.uniweb.no (One.com?):
- narkotika.no
- narkotikainfo.no
- narkotikainformasjon.no
- narkotikapolitiforening.no
- narkotikapolitiforeningen.no
- norsk-narkotikapolitiforening.no
- norsk-narkotikapolitiforening.no
- rusreformen.no
- tegnogsymptomer.no

Domener uten mail (mx):
- narkotikakurs.no


-----

Sub domains
webmail.nnpf.no 	104.37.39.100
butikk.nnpf.no		null ip
stats.nnpf.no		91.207.158.103
ftp.nnpf.no 		5.249.226.17 (uw17.uniweb.no, one com)
www.nnpf.no 		35.228.55.150


FTP. Virker som standard parkert domene

	$ curl ftp.nnpf.no -v
	* Rebuilt URL to: ftp.nnpf.no/
	*   Trying 5.249.226.17...
	* TCP_NODELAY set
	* Connected to ftp.nnpf.no (5.249.226.17) port 21 (#0)
	< 220 Welcome to uniweb.no FTP service
	> USER anonymous
	< 331 Password required for anonymous
	> PASS ftp@example.com
	< 530 Login incorrect.
	* Access denied: 530
	* Closing connection 0
	curl: (67) Access denied: 530

	HTTP: nginx
	HTTPS: Apache
	FTP: 220 Welcome to uniweb.no FTP service
	SSH: SSH-2.0-OpenSSH_7.2p2 Ubuntu-4ubuntu2.6
	HTTP TECH: PHP,7.3.18
	nginx
	HTTPS TECH: PHP,7.3.18

www.nnpf.no => 35.228.55.150 (150.55.228.35.bc.googleusercontent.com)
	HTTP: nginx
	HTTPS: nginx
	SSH: SSH-2.0-OpenSSH_7.6p1 Ubuntu-4ubuntu0.3
	HTTP TECH: nginx
	WordPress
	HTTPS TECH: nginx

	=> Shared WP host

stats.nnpf.no
	Svarer ikke på IPen

	Andre med samme IP:
		mail.bgmo.no
		mail.klokkhammerforlag.no
		mail.mattecompagniet.no
		mail.trappekompaniet.no
		mail.vvsbomlo.no
		stats.kamfest.no
		stats.onestopreporting.com
		stats.uniweb.no
		tuck.as
		webmail.bgmo.no
		webmail.blefjellbooking.no
		webmail.klokkhammerforlag.no
		webmail.steinarmoe.no
		webmail.trappekompaniet.no
		webmail.vvsbomlo.no

webmail.nnpf.no => redirect til roundcube webmail-klient (rcube.uniweb.no)