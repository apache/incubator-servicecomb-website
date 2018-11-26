---
title: "ServiceComb Saga 下载"
lang: cn
ref: release
permalink: /cn/release/saga-downloads/
excerpt: "ServiceComb Saga Downloads"
last_modified_at: 2018-03-28T00:50:43-55:00
---

## 发布包

* Apache ServiceComb (incubating) Saga 0.2.1 (LATEST)
    - 源码 [[src]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-src.zip) [[asc]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-src.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-src.zip.sha512)
    - 发布包 [[Binary]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-bin.zip) [[asc]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-bin.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/servicecomb/servicecomb-saga/0.2.1/apache-servicecomb-saga-distribution-0.2.1-bin.zip.sha512)

* Apache ServiceComb (incubating) Saga 0.2.0
    - 源码 [[src]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-src.zip) [[asc]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-src.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-src.zip.sha512)
    - 发布包 [[Binary]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-bin.zip) [[asc]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-bin.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.2.0/apache-servicecomb-incubating-saga-distribution-0.2.0-bin.zip.sha512)

* Apache ServiceComb (incubating) Saga 0.1.0
    - 源码 [[src]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-src.zip) [[asc]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-src.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-src.zip.sha512)
    - 发布包 [[Binary]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-bin.zip) [[asc]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-bin.zip.asc) [[sha512]](https://apache.org/dyn/closer.cgi/incubator/servicecomb/incubator-servicecomb-saga/0.1.0/apache-servicecomb-incubating-saga-distribution-0.1.0-bin.zip.sha512)


**发布包验证**

使用PGP或SHA签名验证下载文件的完整性是很有必要的。PGP签名可以使用GPG或PGP进行验证，请下载 [KEYS](https://www.apache.org/dist/servicecomb/KEYS)以及相关发行的asc签名文件。

建议从主发行[目录](https://www.apache.org/dist/servicecomb/servicecomb-saga/)中获取这些文件，而不是从镜像中获取这些文件。

 ```
 gpg -i KEYS
 
 or
 
 pgpk -a KEYS
 
 or
 
 pgp -ka KEYS

 ```

要验证二进制文件或源代码，您可以从主发行目录下载相关的asc文件并按照以下指南进行操作。

```
gpg --verify apache-servicecomb-saga********.asc apache-servicecomb-saga-*********

or

pgpv apache-servicecomb-saga-********.asc

or 

pgp apache-servicecomb-saga-********.asc


```

另外，您也可以从主发行[仓库](https://www.apache.org/dist/servicecomb/servicecomb-saga/){:target="_blank"}下载SHA签名并使用sha512sum验证。
