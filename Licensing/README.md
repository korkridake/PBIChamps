# Power BI Licensing 2021

What a user can do in the Power BI service depends on the type of per-user license that they have. The level of access provided by their license depends on whether the workspace being accessed is in a Premium workspace or not. All users of the Power BI service must have a license.

There are two ways for users to get a license. Using self-service sign-up capabilities and their work or school account, users can get their own free, Pro, or Premium Per User license. Or, admins can get a Power BI license subscription and assign licenses to users.

## Questions to Ask

Please ask the following questions in order to determine the appropriate Power BI licensing.

1. How many Power BI users in total are you expecting? 
   * $>$ 500 users 
     * Power BI Premium Per Capacity (PPC) 
   * $\le$ 500 users
     * Power BI Pro
     * Power BI Premium Per User (PPU)
2. Do you need to publish reports to share and collaborate?
   * YES
     * Power BI Pro
     * Power BI Premium Per User (PPU)
   * NO
     * Power BI Premium Per Capacity (PPC) 
3. Do you need to work on paginated reports?
   * YES
     * Power BI Premium Per Capacity (PPC) 
     * Power BI Premium Per User (PPU)
   * NO
     * Power BI Pro
4. Do you need flexibility to deploy reports to on-premise reporting with Power BI report server and Power BI service?
   * YES
     * Power BI Premium Per Capacity (PPC) 
   * NO
     * Power BI Pro
     * Power BI Premium Per User (PPU)
5. Do you want to leverage AI capabilities in Power BI?
   * YES
     * Power BI Premium Per Capacity (PPC) 
     * Power BI Premium Per User (PPU)
   * NO
     * Power BI Pro
6. Will you require the large data model (> 100 GB?)
   * YES
     * Power BI Premium Per Capacity (PPC) 
     * Power BI Premium Per User (PPU)
   * NO
     * Power BI Pro
7. Do you expect any potential use case with Power BI Dataflow?
   * YES
     * Power BI Premium Per Capacity (PPC) 
     * Power BI Premium Per User (PPU)
   * NO
     * Power BI Pro
8. Which refreshing rate is more suitable for your BI needs?
   * 8/day 
     * Power BI Pro
   * 48/day
     * Power BI Premium Per Capacity (PPC) 
     * Power BI Premium Per User (PPU)

Then, sum the score for each option. The highest score is the license you should choose!

### Scorecard Example

License | Score 
--------|---------------
Power BI Pro | 4
Power BI Premium Per User | 5
Power BI Premium Per Capacity | 6

### Feature Matrix

Feature | Power BI Pro  | Power BI Premium per user  | Power BI Premium per capacity 
--------|---------------|----------------------------|-------------------------------
Collaboration and analytics 
Mobile app access  | ● | ● | ●
Publish reports to share and collaborate  | ● | ● |  
Paginated (RDL) reports |  |   | ● | ●
Consume content without a per-user license  |   |   | ●
On-premises reporting with Power BI Report Server  |    |   | ●
Data prep, modeling, and visualization 
Model size limit   | 1 GB  | 100 GB  | 400 GB 
Refresh rate   | 8/day  | 48/day  | 48/day 
Connect to 100+ data sources  | ● | ● | ●
Create reports and visualizations with Power BI Desktop4  | ● | ● | ●
Embed APIs and controls  | ● | ● | ●
AI visuals  | ● | ● | ●
Advanced AI (text analytics, image detection, automated machine learning)  |   | ● | ●
XMLA endpoint read/write connectivity   |   | ● | ●
Dataflows (direct query, linked and computed entities, enhanced compute engine)  |    | ● | ●
Analyze data stored in Azure Data Lake Storage  |   | ● | ●
Governance and administration 
Data security and encryption  | ● | ● | ●
Metrics for content creation, consumption, and publishing  | ● | ● | ●
Application lifecycle management   |    | ● | ●
Multi-geo deployment management  |    |    | ●
Bring your own key (BYOK)  |   |   | ●
Autoscale add-on availability (preview)  |   |   | ●
Maximum storage  | 10 GB/user  | 100 TB  | 100 TB 

## How to Choose the Power BI Premium Capacity SKUs

If your choice of Enterprise BI deployment is either Power BI Premium (P-SKU) or Power BI Embedded (E-SKU), please determine SKU memory and computing power from the following table:

Capacity Nodes | Total v-cores | Backend v-cores | RAM (GB) | Frontend v-cores | DirectQuery/Live Connection (per sec) | Model Refresh Parallelism
---------------|---------------|-----------------|----------|------------------|---------------------------------------|--------------------------
EM1/A1 | 1 | 0.5 | 2.5 | 0.5 | 3.75 | 1
EM2/A2 | 2 | 1 | 5 | 1 | 7.5 | 2
EM3/A3 | 4 | 2 | 10 | 2 | 15 | 3
P1/A4 | 8 | 4 | 25 | 4 | 30 | 6
P2/A5 | 16 | 8 | 50 | 8 | 60 | 12
P3/A6 | 32 | 16 | 100 | 16 | 120 | 24
P4 | 64 | 32 | 200 | 32 | 240 | 48
P5 | 128 | 64 | 400 | 64 | 480 | 96

✔️ Microsoft recommends that enterprises buy Power BI Premium, an enterprise-grade, self-service cloud BI solution. We recommend ISVs buy Power BI Embedded for its cloud-powered embedded analytics components. However, a customer has no restriction on which product to buy.

## How to Request for Power BI Trial

* [Sign up or purchase the Power BI service as an individual - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/fundamentals/service-self-service-signup-for-power-bi#use-self-service-sign-up-to-get-an-individual-power-bi-license)
* Users who want to test drive **Power BI Premium Capacity**, please contact Microsoft Team, and we are happy to assist in your specific request.

## Additional Resource

* [Power BI licensing for users in your organization - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-licensing-organization)
* [Capacity and SKUs in Power BI embedded analytics - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedded-capacity)
* [Frequently asked questions about Power BI embedded analytics - Power BI | Microsoft Docs](https://docs.microsoft.com/en-us/power-bi/developer/embedded/embedded-faq)