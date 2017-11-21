# raid-troubleshoting

Since this has come up, and I can't remember how to even install the megacli utility - let alone all the cryptic commands I may need to run, this seems like as good a spot as any to dump some info.

Any expected `yum install megacli` success seems thwarted by some licensing requirements that appear to only be satisfied by agreeing to the terms offered as a "pop-up" when you go directly to the Broadcom website to download the package (which offers a .rpm file in a zip file...) https://www.broadcom.com/support/download-search?dk=megacli (most current version as of 11/20/17 is: 8.07.14-1) or in a pinch, you could use an earlier version which (currently) appears to be available from here: http://download2.boulder.ibm.com/sar/CMA/XSA/ibm_utl_sraidmr_megacli-{{ megacli_version }}_linux_32-64.zip.


* http://wordpress.hawkless.id.au/index.php/2016/10/12/megacli-on-centos-7/
* https://calomel.org/megacli_lsi_commands.html
* https://tipstricks.itmatrix.eu/checking-the-health-of-lsi-logic-symbios-logic-megaraid-sas-2108-raid-controller/
* Awesome way to combine megacli with smartctl to get super-fine-grained detail on harddisks: http://docs.ovh.ca/en/faqs-hdd-serial.html#how-do-i-find-the-serial-number-of-my-hard-disk
