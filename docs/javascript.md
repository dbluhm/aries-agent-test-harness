# Aries Framework JavaScript Interoperability

## Runsets with AFJ

| Runset | ACME<br>(Issuer) | Bob<br>(Holder) | Faber<br>(Verifier) | Mallory<br>(Holder) | Scope | Results | 
| ------ | :--------------: | :-------------: | :----------------: | :-----------------: | ----- | :-----: | 
| [acapy-afj](#runset-acapy-afj) | acapy-main<br>0.7.0 | javascript<br>0.1.0-alpha.233 | acapy-main<br>0.7.0 | acapy-main<br>0.7.0 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript/reports/latest/index.html?redirect=false#behaviors) |
| [acapy-dotnet-javascript](#runset-acapy-dotnet-javascript) | acapy-main<br>0.7.0 | javascript<br>0.1.0-alpha.233 | dotnet-master<br> | acapy-main<br>0.7.0 | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [afj-acapy](#runset-afj-acapy) | javascript<br>0.1.0-alpha.233 | acapy-main<br>0.7.0 | javascript<br>0.1.0-alpha.233 | javascript<br>0.1.0-alpha.233 | AIP 1.0 | [**8 / 17<br>47%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [afj-dotnet](#runset-afj-dotnet) | javascript<br>0.1.0-alpha.233 | dotnet-master<br> | javascript<br>0.1.0-alpha.233 | javascript<br>0.1.0-alpha.233 | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-dotnet/reports/latest/index.html?redirect=false#behaviors) |
| [afj](#runset-afj) | javascript<br>0.1.0-alpha.233 | javascript<br>0.1.0-alpha.233 | javascript<br>0.1.0-alpha.233 | javascript<br>0.1.0-alpha.233 | AIP 1.0 | [**17 / 17<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/javascript/reports/latest/index.html?redirect=false#behaviors) |
| [dotnet-javascript](#runset-dotnet-javascript) | dotnet-master<br> | javascript<br>0.1.0-alpha.233 | dotnet-master<br> | dotnet-master<br> | AIP 1.0 | [**12 / 12<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-javascript/reports/latest/index.html?redirect=false#behaviors) |

## Runset Notes

### Runset **acapy-afj**

Runset Name: ACA-PY to AFJ

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Fri Jul 23 01:30:43 UTC 2021*
```

#### Current Runset Status

Most of the tests are running. The tests not passing are being investigated.

*Status Note Updated: 2021.03.18*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-javascript/reports/latest)


### Runset **acapy-dotnet-javascript**

Runset Name: ACA-PY to AF-.NET to AFJ

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Fri Jul 23 01:41:59 UTC 2021*
```

#### Current Runset Status

All tests are working, except for three tests that include Faber in the test run as an issuer.
These tests are; T001-RFC0037@1.2, T001.2-RFC0037@1.2, T001.4-RFC0037@1.1 . Further investigation 
is required to determine the issue in these three tests.

*Status Note Updated: 2021.03.18*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-javascript-f-dotnet/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-javascript-f-dotnet/reports/latest)


### Runset **afj-acapy**

Runset Name: AFJ to ACA-PY

```tip
**Latest results: 8 out of 17 (47%)**


*Last run: Fri Jul 23 02:20:53 UTC 2021*
```

#### Current Runset Status

All AIP10 tests are currently running.

*Status Note Updated: 2021.03.17*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript-b-acapy/reports/latest)


### Runset **afj-dotnet**

Runset Name: AFJ to AF-.NET

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Fri Jul 23 02:00:12 UTC 2021*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.03.05*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/javascript-b-dotnet/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript-b-dotnet/reports/latest)


### Runset **afj**

Runset Name: AFJ to AFJ

```tip
**Latest results: 17 out of 17 (100%)**


*Last run: Fri Jul 23 02:13:08 UTC 2021*
```

#### Current Runset Status

All of the tests being executed in this runset are passing.

*Status Note Updated: 2021.03.05*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/javascript/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/javascript/reports/latest)


### Runset **dotnet-javascript**

Runset Name: AF-.NET to AFJ

```tip
**Latest results: 12 out of 12 (100%)**


*Last run: Fri Jul 23 02:22:45 UTC 2021*
```

#### Current Runset Status

More tests are failing than are passing when Aries Framework .NET is playing the issuer role. More investigation is needed.

*Status Note Updated: 2021.03.18*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/dotnet-b-javascript/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/dotnet-b-javascript/reports/latest)

Jump back to the [interoperability summary](./README.md).

