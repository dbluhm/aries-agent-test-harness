# Aries Framework Go Interoperability

## Runsets with AF-Go

| Runset | ACME<br>(Issuer) | Bob<br>(Holder) | Faber<br>(Verifier) | Mallory<br>(Holder) | Scope | Results | 
| ------ | :--------------: | :-------------: | :----------------: | :-----------------: | ----- | :-----: | 
| [acapy-afgo](#runset-acapy-afgo) | acapy-main<br>0.7.0 | afgo-interop<br>unknown | acapy-main<br>0.7.0 | acapy-main<br>0.7.0 | pre-AIP 2.0 | [**3 / 3<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-afgo/reports/latest/index.html?redirect=false#behaviors) |
| [afgo-acapy](#runset-afgo-acapy) | afgo-interop<br>unknown | acapy-main<br>0.7.0 | afgo-interop<br>unknown | afgo-interop<br>unknown | pre-AIP 2.0 | [**3 / 3<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/afgo-b-acapy/reports/latest/index.html?redirect=false#behaviors) |
| [afgo](#runset-afgo) | afgo-master<br>unknown | afgo-master<br>unknown | afgo-master<br>unknown | afgo-master<br>unknown | pre-AIP 2.0 | [**6 / 6<br>100%**](https://allure.vonx.io/api/allure-docker-service/projects/afgo/reports/latest/index.html?redirect=false#behaviors) |

## Runset Notes

### Runset **acapy-afgo**

Runset Name: ACA-PY to AF-Go

```tip
**Latest results: 3 out of 3 (100%)**


*Last run: Fri Jul 23 01:22:29 UTC 2021*
```

#### Current Runset Status

None of the tests are currently working and issues have been created to try to determine three identified issues.
One might be in the test suite, while two others appear to be in the Aries Framework Go.

*Status Note Updated: 2021.03.05*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/acapy-b-afgo/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/acapy-b-afgo/reports/latest)


### Runset **afgo-acapy**

Runset Name: AF-Go to ACA-PY

```tip
**Latest results: 3 out of 3 (100%)**


*Last run: Fri Jul 23 01:55:11 UTC 2021*
```

#### Current Runset Status

None of the tests are currently working and issues have been created to try to determine three identified issues.
One might be in the test suite, while two others appear to be in the Aries Framework Go.

*Status Note Updated: 2021.03.17*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/afgo-b-acapy/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/afgo-b-acapy/reports/latest)


### Runset **afgo**

Runset Name: AF-Go to AF-Go

```tip
**Latest results: 6 out of 6 (100%)**


*Last run: Fri Jul 23 02:02:58 UTC 2021*
```

#### Current Runset Status

The tests that use an implicit invitation are not currently working. The issue is being investigated -- this feature may not be
supported in Aries Framework Go.

*Status Note Updated: 2021.03.05*

#### Runset Details

- Results grouped by [executed Aries RFCs executed](https://allure.vonx.io/api/allure-docker-service/projects/afgo/reports/latest/index.html?redirect=false#behaviors)
- Results by [history](https://allure.vonx.io/allure-docker-service-ui/projects/afgo/reports/latest)

Jump back to the [interoperability summary](./README.md).

