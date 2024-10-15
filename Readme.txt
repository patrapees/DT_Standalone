#This program required Java runtime environment version 1.8 later
#Check Java Program
1. open command prompt
2. run command> java -version

#Install Program
1. Download program
2. Create Directory c:\certificate
3. Extract all download files to c:\certificate
4. Change file RmStandalone_Sign....jar (lastest) to DT_Standalone.jar
5. (for example) Make PDF Source Directory, Create Directory c:\certificate\pdf_source
6. (for example) Make PDF Output directory, Create Directory c:\certificate\pdf_digital

#Run Program
1. open command prompt
2. run command> cd c:\certificate
3. run command> java -jar DT_standalone.jar -cf_ca *school* -cf_cd c:\certificate\config_standalone.lib -cfd_ds c:\certificate\pdf_source -cfd_dd c:\certificate\pdf_digital -needsplit n

#Certificate Validation
1. By Acrobat Reader
2. By Web Portal https://www.etda.or.th/th/Our-Service/Digital-Trusted-services-Infrastructure/TEDA/Web-Validation.aspx
3. By Web Portal http://app.oreg.rmutt.ac.th/DigitalCertificate/

Any question, please contact Patrapee.s@en.rmutt.ac.th Mobile 0863649701
