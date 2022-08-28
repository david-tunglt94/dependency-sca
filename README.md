# dependency-sca
dependency-sca is an open source tool performing a best effort analysis of 3rd party dependencies

### lib
List NVD (National Vulnerability Database - NVD) CVE (Common Vulnerabilities and Exposures - CVE)
https://drive.google.com/file/d/1ySH4pzdlm16BIOebsHiov2fsK91DDjCP/view?usp=sharing

### reports
Result scan dependency

### docker
```docker
docker build -t tbdavid94/sca:tagname .
docker push tbdavid94/sca:tagname
docker pull tbdavid94/sca:tagname
```

### NOTE
Unzip odc.mv.db =>lib/data...
