# KOHA_OPAC_Calendar
## To add Calendar on OPAC Interface, use these files. Download these files.
## Change the Code of Line number 42 in holidays_opac.pl .
  >>> my $branch="[your branch]";
  Replace [your branch] with your Library Branch Code.
  
## Upload holidays_opac.pl in /koha/intranet/cgi-bin/tools folder and holidays_OPAC.tt in /koha/intranet/htdocs/intranet-tmpl/prog/en/modules/tools folder.
## Then give permission (chmod 755 holidays_opac.pl and chmod 644 holidays_OPAC.tt).
## Now open http://[your IP]:8080/cgi-bin/koha/tools/holidays_opac.pl in browser.

## <!!!-- Important: Customize the Holidays and Name according to your Library -!!!>

## Powered by KOHA | Customized by Suzon Das ####

