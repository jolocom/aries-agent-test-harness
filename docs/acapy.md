# Aries Cloud Agent Python Interoperability

## Runsets with ACA-Py

| Runset | ACME<br>(Issuer) | Bob<br>(Holder) | Faber<br>(Verifier) | Mallory<br>(Holder) | Scope | Results | 
| ------ | :--------------: | :-------------: | :----------------: | :-----------------: | ----- | :-----: | 
| [acapy-afgo](#runset-acapy-afgo) | acapy-main<br>0.7.3 | afgo-interop<br>unknown | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | pre-AIP 2.0 | [**10 / 10<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-afgo/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-afj](#runset-acapy-afj) | acapy-main<br>0.7.3 | javascript<br>0.1.0 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-aip10](#runset-acapy-aip10) | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-aip10/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-aip20](#runset-acapy-aip20) | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 2.0 | [**32 / 32<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-aip20/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-ariesvcx](#runset-acapy-ariesvcx) | acapy-main<br>0.7.3 | aries-vcx<br>1.0.0 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**31 / 31<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-aries-vcx/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-dotnet-javascript](#runset-acapy-dotnet-javascript) | acapy-main<br>0.7.3 | javascript<br>0.1.0 | dotnet-master<br> | acapy-main<br>0.7.3 | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-dotnet](#runset-acapy-dotnet) | acapy-main<br>0.7.3 | dotnet-master<br> | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**26 / 27<br>96%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-findy](#runset-acapy-findy) | acapy-main<br>0.7.3 | findy<br>0.25.30 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-verity](#runset-acapy-verity) | verity<br>1.0 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**0 / 2<br>0%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-verity/reports/latest/index.html?redirect=false#behaviors) |
| [afgo-acapy](#runset-afgo-acapy) | afgo-interop<br>unknown | acapy-main<br>0.7.3 | afgo-interop<br>unknown | afgo-interop<br>unknown | pre-AIP 2.0 | [**10 / 10<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/afgo-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [afj-acapy](#runset-afj-acapy) | javascript<br>0.1.0 | acapy-main<br>0.7.3 | javascript<br>0.1.0 | javascript<br>0.1.0 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [ariesvcx-acapy](#runset-ariesvcx-acapy) | aries-vcx<br>1.0.0 | acapy-main<br>0.7.3 | aries-vcx<br>1.0.0 | aries-vcx<br>1.0.0 | AIP 1.0 | [**20 / 31<br>64%**](https://allure.vonx.io/api/allure-docker-service/projects/aries-vcx-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [dotnet-acapy](#runset-dotnet-acapy) | dotnet-master<br> | acapy-main<br>0.7.3 | dotnet-master<br> | dotnet-master<br> | AIP 1.0 | [**5 / 12<br>41%**](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [findy-acapy](#runset-findy-acapy) | findy<br>0.25.30 | acapy-main<br>0.7.3 | findy<br>0.25.30 | findy<br>0.25.30 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors) |

## Runset Notes

### Runset **acapy-afgo**

Runset Name: ACA-PY to AF-Go

```tip
**Latest results: 10 out of 10 (100%)**


*Last run: Wed Jan 26 01:34:17 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.27*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-afgo/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-afgo/reports/latest)


### Runset **acapy-afj**

Runset Name: ACA-PY to AFJ

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Wed Jan 26 01:48:33 UTC 2022*
```

#### Current Runset Status

Most of the tests are running. The tests not passing are being investigated.

*Status Note Updated: 2021.03.18*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-javascript/reports/latest)


### Runset **acapy-aip10**

Runset Name: ACA-PY to ACA-Py

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Wed Jan 26 01:50:03 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.03.18*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-aip10/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-aip10/reports/latest)


### Runset **acapy-aip20**

Runset Name: ACA-PY to ACA-Py

```tip
**Latest results: 32 out of 32 (100%)**


*Last run: Wed Jan 26 02:10:03 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.03.16*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-aip20/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-aip20/reports/latest)


### Runset **acapy-ariesvcx**

Runset Name: acapy to aries-vcx

```tip
**Latest results: 31 out of 31 (100%)**


*Last run: Wed Jan 26 03:04:40 UTC 2022*
```

#### Current Runset Status
```warning
No test status note is available for this runset. Please update: .github/workflows/test-harness-acapy-ariesvcx.yml.
```

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-aries-vcx/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-aries-vcx/reports/latest)


### Runset **acapy-dotnet-javascript**

Runset Name: ACA-PY to AF-.NET to AFJ

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Wed Jan 26 01:55:59 UTC 2022*
```

#### Current Runset Status

All tests are working, except for three tests that include Faber in the test run as an issuer.
These tests are; T001-RFC0037@1.2, T001.2-RFC0037@1.2, T001.4-RFC0037@1.1 . Further investigation 
is required to determine the issue in these three tests.

*Status Note Updated: 2021.03.18*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-javascript-f-dotnet/reports/latest)


### Runset **acapy-dotnet**

Runset Name: ACA-PY to AF-.NET

```tip
**Latest results: 26 out of 27 (96%)**


*Last run: Wed Jan 26 02:09:50 UTC 2022*
```

#### Current Runset Status

The majority of tests are running and passing. T013-HIPE0011 is failing due to the Aries Framework Dotnet not supporting
presentations containing a non-revocation interval, with a non-revocable credential. This issue is being tracked in 
https://github.com/hyperledger/aries-framework-dotnet/issues/184

*Status Note Updated: 2021.04.08*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-dotnet/reports/latest)


### Runset **acapy-findy**

Runset Name: ACA-PY to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Wed Jan 26 02:27:54 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-findy/reports/latest)


### Runset **acapy-verity**

Runset Name: ACA-PY to Verity

```tip
**Latest results: 0 out of 2 (0%)**


*Last run: Wed Jan 26 02:32:08 UTC 2022*
```

#### Current Runset Status

All the Connection tests are running. All tests are passing

*Status Note Updated: 2021.09.13*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-verity/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-verity/reports/latest)


### Runset **afgo-acapy**

Runset Name: AF-Go to ACA-PY

```tip
**Latest results: 10 out of 10 (100%)**


*Last run: Wed Jan 26 02:01:23 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.27*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/afgo-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/afgo-b-acapy/reports/latest)


### Runset **afj-acapy**

Runset Name: AFJ to ACA-PY

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Wed Jan 26 02:10:54 UTC 2022*
```

#### Current Runset Status

All AIP10 tests are currently running.

*Status Note Updated: 2021.03.17*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript-b-acapy/reports/latest)


### Runset **ariesvcx-acapy**

Runset Name: aries-vcx to acapy

```tip
**Latest results: 20 out of 31 (64%)**


*Last run: Wed Jan 26 03:00:44 UTC 2022*
```

#### Current Runset Status
```warning
No test status note is available for this runset. Please update: .github/workflows/test-harness-ariesvcx-acapy.yml.
```

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/aries-vcx-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/aries-vcx-b-acapy/reports/latest)


### Runset **dotnet-acapy**

Runset Name: AF-.NET to ACA-PY

```tip
**Latest results: 5 out of 12 (41%)**


*Last run: Wed Jan 26 02:23:58 UTC 2022*
```

#### Current Runset Status

More tests are failing than are passing when Aries Framework .NET is playing the issuer role. More investigation is needed.

*Status Note Updated: 2021.03.17*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/dotnet-b-acapy/reports/latest)


### Runset **findy-acapy**

Runset Name: findy to ACA-PY

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Wed Jan 26 02:27:31 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-acapy/reports/latest)

Jump back to the [interoperability summary](./README.md).

