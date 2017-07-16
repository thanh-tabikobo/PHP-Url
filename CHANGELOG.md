# CHANGELOG

## 1.1.4 - 2017-07-16
* Deleted `Josantonius\Url\Exception\UrlException` class.
* Deleted `Josantonius\Url\Exception\Exceptions` abstract class.
* Deleted `Josantonius\Url\Exception\UrlException->__construct()` method.

## 1.1.3 - 2017-07-09
* Added option to analyze concrete urls in some methods.

## 1.1.2 - 2017-05-08
* Now you can choose to place backslash at the beginning, end or both ends in the addBackslash() method.

* The getUriMethods() method was improved to prevent it from replacing single characters that also matched.

## 1.1.1 - 2017-03-18
* Some files were excluded from download and comments and readme files were updated.

## 1.1.0 - 2017-02-28
* Added `Josantonius\Url\Url::getBaseUrl()` method.

## 1.1.0 - 2017-02-28
* Added `Josantonius\Url\Tests\UrlTest::testGetBaseUrl()` method.

## 1.0.0 - 2017-02-02
* Added `Josantonius\Url\Url` class.
* Added `Josantonius\Url\Url::getCurrentPage()` method.
* Added `Josantonius\Url\Url::getProtocol()` method.
* Added `Josantonius\Url\Url::isSSL()` method.
* Added `Josantonius\Url\Url::getDomain()` method.
* Added `Josantonius\Url\Url::getUri()` method.
* Added `Josantonius\Url\Url::getUriMethods()` method.
* Added `Josantonius\Url\Url::getPort()` method.
* Added `Josantonius\Url\Url::addBackslash()` method.
* Added `Josantonius\Url\Url::previous()` method.
* Added `Josantonius\Url\Url::redirect()` method.
* Added `Josantonius\Url\Url::autoLink()` method.
* Added `Josantonius\Url\Url::generateSafeSlug()` method.
* Added `Josantonius\Url\Url::segment()` method.
* Added `Josantonius\Url\Url::getFirstSegment()` method.
* Added `Josantonius\Url\Url::getLastSegment()` method.

## 1.0.0 - 2017-02-02
* Added `Josantonius\Url\Exception\UrlException` class.
* Added `Josantonius\Url\Exception\Exceptions` abstract class.
* Added `Josantonius\Url\Exception\UrlException->__construct()` method.

## 1.0.0 - 2017-02-02
* Added `Josantonius\Url\Tests\UrlTest` class.
* Added `Josantonius\Url\Tests\UrlTest::testGetCurrentPage()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGetProtocol()` method.
* Added `Josantonius\Url\Tests\UrlTest::testIsSSL()` method.
* Added `Josantonius\Url\Tests\UrlTest::getDomain()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGetUri()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGetPort()` method.
* Added `Josantonius\Url\Tests\UrlTest::testAddBackslash()` method.
* Added `Josantonius\Url\Tests\UrlTest::testPrevious()` method.
* Added `Josantonius\Url\Tests\UrlTest::testRedirect()` method.
* Added `Josantonius\Url\Tests\UrlTest::testAutoLink()` method.
* Added `Josantonius\Url\Tests\UrlTest::testCustomAutoLink()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGenerateSafeSlug()` method.
* Added `Josantonius\Url\Tests\UrlTest::testSegment()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGetFirstSegment()` method.
* Added `Josantonius\Url\Tests\UrlTest::testGetLastSegment()` method.