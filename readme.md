#Detecting the common protein domains for the given organisms and search terms.

 we will report that  show the users INTERPRO statistics  & Common INTERPROs.

##Resources
* Database 
 - Uniprot
* Web Service 
 - Uniprot Rest Api
* Tools 
 - Perl 
 - Unix Commands
 
##Usage
```
perl script.pl -o 9640 10090 "Rattus norvegicus" -s "Glucose Metabolism" -out "html"
```
To run script;

 - We need to give taxonomy ids or scientific names or both after -o.
 - Also we can give search term after -s. 
 - For output, give a format after -out (html, txt, all).

##Team Members 

  * [Meltem Demir] (https://github.com/demirmeltem)
  * [Cenk Töremiş] (https://github.com/cenktrms)
  * [Mehmet Ersan Uzun] (https://github.com/mersanuzun)
