# Findy Agent Interoperability

## Runsets with Findy

| Runset | ACME<br>(Issuer) | Bob<br>(Holder) | Faber<br>(Verifier) | Mallory<br>(Holder) | Scope | Results | 
| ------ | :--------------: | :-------------: | :----------------: | :-----------------: | ----- | :-----: | 
| [acapy-findy](#runset-acapy-findy) | acapy-main<br>0.7.3 | findy<br>0.25.31 | acapy-main<br>0.7.3 | acapy-main<br>0.7.3 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [afj-findy](#runset-afj-findy) | javascript<br>0.1.0 | findy<br>0.25.31 | javascript<br>0.1.0 | javascript<br>0.1.0 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [dotnet-findy](#runset-dotnet-findy) | dotnet-master<br> | findy<br>0.25.30 | dotnet-master<br> | dotnet-master<br> | AIP 1.0 | [**2 / 17<br>11%**](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-findy/reports/latest/index.html?redirect=false#behaviors) |
| [findy-acapy](#runset-findy-acapy) | findy<br>0.25.31 | acapy-main<br>0.7.3 | findy<br>0.25.31 | findy<br>0.25.31 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [findy-dotnet](#runset-findy-dotnet) | findy<br>0.25.31 | dotnet-master<br> | findy<br>0.25.31 | findy<br>0.25.31 | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [findy-javascript-dotnet](#runset-findy-javascript-dotnet) | findy<br>0.25.31 | javascript<br>0.1.0 | dotnet-master<br> | findy<br>0.25.31 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [findy-javascript](#runset-findy-javascript) | findy<br>0.25.31 | javascript<br>0.1.0 | findy<br>0.25.31 | findy<br>0.25.31 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript/reports/latest/index.html?redirect=false#behaviors) |
| [findy](#runset-findy) | findy<br>0.25.31 | findy<br>0.25.31 | findy<br>0.25.31 | findy<br>0.25.31 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/findy/reports/latest/index.html?redirect=false#behaviors) |

## Runset Notes

### Runset **acapy-findy**

Runset Name: ACA-PY to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 02:22:27 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-findy/reports/latest)


### Runset **afj-findy**

Runset Name: AFJ to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 02:30:23 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are failing. There is an issue with afj sending the connection 
response, and throws an error processing inbound message.

*Status Note Updated: 2021.09.28*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript-b-findy/reports/latest)


### Runset **dotnet-findy**

Runset Name: dotnet to findy

```tip
**Latest results: 2 out of 17 (11%)**


*Last run: Sat Jan 22 04:16:14 UTC 2022*
```

#### Current Runset Status

Two connection tests are passing out of Nineteen total. There are multiple issues in Issue Credential and Proof
with dotnet as the issuer and findy as the holder.

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/dotnet-b-findy/reports/latest)


### Runset **findy-acapy**

Runset Name: findy to ACA-PY

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 02:23:45 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-acapy/reports/latest)


### Runset **findy-dotnet**

Runset Name: findy to dotnet

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Thu Jan 27 02:24:25 UTC 2022*
```

#### Current Runset Status

All test scenarios are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-dotnet/reports/latest)


### Runset **findy-javascript-dotnet**

Runset Name: findy to AFJ to AF-.NET

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 01:51:57 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-javascript-f-dotnet/reports/latest)


### Runset **findy-javascript**

Runset Name: findy to AFJ

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 02:22:33 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing. 

*Status Note Updated: 2021.10.15*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy-b-javascript/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy-b-javascript/reports/latest)


### Runset **findy**

Runset Name: findy to findy

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Thu Jan 27 02:48:32 UTC 2022*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.09.14*

#### Runset Details

- [Results by executed Aries RFCs](https://allure.vonx.io/api/allure-docker-service/projects/findy/reports/latest/index.html?redirect=false#behaviors)
- [Test execution history](https://allure.vonx.io/allure-docker-service-ui/projects/findy/reports/latest)

Jump back to the [interoperability summary](./README.md).

