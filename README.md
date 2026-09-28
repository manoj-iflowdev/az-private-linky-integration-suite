# az-private-linky-integration-suite
SAP Integration Suite artifacts to get you started with SAP BTP Private Link Service for Azure.

The blog post series on this topic can be found [here](https://blogs.sap.com/2021/07/13/btp-private-linky-swear-with-azure-business-as-usual-for-iflows/).

The package contains two iFlows. One configured against the CAP implementation and one for Java. They differ due to the chosen router configuration. They can be adapted as required.

Additional Resources |
--- |
[CAP backend Project](https://github.com/MartinPankraz/az-private-linky-cap) |
[Java backend Project using SAP Cloud SDK](https://github.com/MartinPankraz/az-private-linky) |
[Fiori Project consuming above backends](https://github.com/MartinPankraz/az-products-ui) |
[SAP's official blog](https://blogs.sap.com/2021/06/28/sap-private-link-service-beta-is-available/) |

The /sap/opu/odata/sap/epm_ref_apps_prod_man_srv OData service was used for this project.

## Project context
Azure Private Link Service allows private connectivity between resources running on Azure in different environments. That includes SAP's Business Technology Platform when provisioned on Azure. SAP made that functionality available via a CloudFoundry Service.

This provides a managed component to expose SAP backends to BTP on Azure without the need for a Cloud Connector. For this example, development was performed against S4 primarily, but anything executable in a service behind the Azure load balancer is reachable. This involves, for instance, ECC, BO, PI/PO, SolMan, SAP CAR etc.

![Architecture overview](/linky-cpi-overview.png)

Reach out via the GitHub Issues page of this repository to discuss this project further.

## Maintainer
Manoj Gali is a Senior SAP CPI Consultant with over 5 years of experience in SAP integration technologies. He specializes in SAP CPI, PI/PO, and hybrid integration landscapes, with proven expertise in designing, developing, and optimizing scalable integration solutions. His technical focus includes Groovy Scripting, XSLT, and User-Defined Functions (UDFs) to ensure secure, high-performance data exchange across SAP and non-SAP systems.

Contact:
- Email: manoj.gali695@gmail.com