# cloud-architecture
Cloud Architecture Notes

* Cloud Architecture Definition: Cloud architecture involves configuring cloud and traditional technologies to meet business requirements.
* Optimization: Good cloud architecture should be optimized to minimize costs, maximize efficiency, and meet business needs with minimal risk.
* Comprehensive Design: It includes application and infrastructure design, deployment planning, operations planning, security design, and database design.
* Continuous Improvement: The architecture should be continuously optimized to adapt to future business needs.

## tools and knowledge
* Advanced Knowledge: Cloud architects should have an advanced understanding of cloud technologies, including storage, computing, databases, and security.
* Open-mindedness: It's essential to consider various technologies and solutions, even if they aren't a perfect fit for every problem.
* Processes and Tools: Utilize predefined processes and tools to efficiently perform tasks like system inventory, data management, and security planning. However, remember that tools can't automate all aspects of architecture design.

## business case 
* Business Justification: Always start cloud projects with a business case to justify spending and risk.
* Utility and Value: Ensure the cloud architecture adds value to the business before making design decisions.
* Cost-Benefit Analysis: Consider hard and soft costs and benefits to make informed design decisions and understand trade-offs.

## costs
* Soft Costs: These include less obvious expenses like retraining and hiring, which are difficult to calculate precisely.
* Soft Benefits: Benefits such as increased agility are significant but hard to quantify in exact terms.
* Importance: Both soft costs and benefits are crucial in estimating the overall impact of moving to the cloud, despite their complexity in measurement.
* Hard Costs include measurable expenses like cloud storage usage, which can be defined in dollar terms.
* Hard Benefits: Savings from not having to purchase and maintain physical storage hardware, which can also be quantified in dollar terms.
* FinOps: Financial operations processes help track and control spending on cloud resources, allocate costs, and identify savings and budget overruns.

## optimization 
* Technology Bias: Cloud architects may favor technologies they are familiar with, which can influence design decisions.
* Optimization Importance: Ensuring cloud solutions are optimized is crucial to avoid unnecessary costs and maximize business value.
* Underoptimized Solutions: Many cloud solutions are not fully optimized, leading to higher costs and less efficiency. Regular audits can help identify and correct these issues.

## ai
* Intelligent Resource Management: AI predicts resource needs in real-time, optimizing cloud infrastructure for better performance at lower costs.
* Predictive Architecture: AI-driven systems can proactively predict failures, optimize data paths, and improve uptime and user experience.
* Adaptive Security: AI enables real-time threat detection and automatic response, continuously adjusting security measures based on emerging threats and system behavior.

## complexity
* Complexity vs. Optimization: Cloud architects often design complex, heterogeneous solutions to leverage the best combinations of cloud services, balancing complexity with optimization.
* Multi-Cloud Challenges: Managing multiple cloud providers can increase complexity, requiring skilled personnel to handle different storage systems and technologies.
* Business Value: Despite the added complexity and costs, the goal remains to maximize business value by selecting the best-of-breed solutions tailored to specific needs.

## issues/challenge
* Operational Inefficiencies: xer. Faces significant operational challenges, including delays in quote generation, inventory inaccuracies, and production downtime.
* Financial Impact: These inefficiencies result in substantial financial losses, including $2 million monthly losses and $5 million wasted annually on incorrect forecasting.
* Business Case Creation: Your task is to determine if cloud computing can address these issues and what business benefits it might bring to xer.

```
Company Overview: Xer is a mid-size manufacturer facing severe operational and financial challenges.
Operational Inefficiencies:
Quote Generation Delays: 24-hour delays in generating quotes are crippling sales.
Inventory Accuracy: Only 35% accuracy in inventory management, leading to stockouts and overstock.
Production Downtime: 25% downtime in production lines, resulting in significant financial losses.

Customer Churn: The company is experiencing a 15% increase in customer churn year-over-year.
Financial Impact:
Monthly Losses: Current losses are estimated at $2 million per month.
Forecasting Errors: $5 million wasted annually due to incorrect forecasting.
Profit Margins: Shrinking by 3% quarterly.
Market Share: Declined by 12% in the past year.
```

## storage design
* Requirement Clarity: Clearly define and understand your storage requirements to make informed design decisions.
* Key Attributes: Assess capacity, speed, disaster recovery, application interfaces, growth model, management, and security when choosing cloud storage.
* Foundation Importance: Storage is fundamental to cloud computing architecture, and getting it right ensures a solid foundation for your cloud solutions.

## compute power
* Compute Requirements: Identify the right CPU, memory size, and operating system for your cloud computing solution.
* Performance Factors: Consider speed, disaster recovery, application interfaces, management, and security when designing compute resources.
* Cost and Efficiency: Balance under- and overspending by selecting appropriate computing resources to avoid unnecessary costs and ensure optimal performance.

## database design
* Database Options: Cloud providers offer various databases, including cloud-native, single cloud provider, and third-party databases.
* Key Considerations: Focus on capacity, speed, analytics, management, security, and disaster recovery when selecting a cloud database.
* Requirement Definition: Establishing your requirements upfront ensures an optimized solution that brings value to the business.

## security design 
* Holistic Security: Security must be systemic and integrated across all cloud-based systems and resources.
* Security Solutions: Key solutions include identity and access management (IAM), encryption, multifactor authentication, disaster recovery, and application interfaces.
* Custom Approaches: Security requirements vary widely and should be tailored to specific cloud solution needs, considering both application-specific and system-wide security measures.

## governance
* Governance Types: Understand different types of governance in cloud computing, including cost governance, resource governance, and API/service governance.
* Policy Implementation: Define governance policies to limit the use of money, cloud resources, and APIs, ensuring efficient and controlled usage.
* Integration with Security: Governance systems should link to other systems, such as security, to create a cohesive and well-managed cloud environment.
* cost governance | resources governance | API/Service governance

## cloudops/finops
* CloudOps Requirements: Defining CloudOps requirements involves determining the number of cloud systems that need to be monitored, maintained, and adjusted after deployment. Proper operation is crucial for the business to perceive the cloud-based systems as successful.
Performance Operations (PerfOps): Focuses on ensuring the system performs according to business requirements. It's not always about high speed but meeting the necessary performance levels to avoid unnecessary costs.
* Security Operations (SecOps): Involves maintaining the core security system to meet expectations continuously.
* Governance Operations (GovOps): Ensures that all governance systems are operating effectively on an ongoing basis.
* Data Operations (DataOps): Keeps databases functioning as expected.
* Application Operations (AppOps): Ensures applications operate consistently to meet business needs.
* Other Operations: Includes edge computing, container operations, and website operations, among others.
* Monitoring and Operations Technologies: Selecting the right tools for monitoring and operations is essential. This includes AI-enabled operations (AIOps) that monitor systems and deploy self-healing functions to fix issues proactively.
* AI Integration: Leveraging AI capabilities to automatically adjust system operations without human intervention can significantly enhance efficiency.
* Operational Success: The long-term success of your cloud solution is judged based on its operations. Avoiding operational problems should always be a priority to ensure the system is seen as a success by the business.

## others
* Evolving Technologies: The video highlights the importance of staying open-minded about new technologies that arise each year, such as edge computing, IoT, AI-based cloud services, serverless computing, and containers. These technologies present new requirements for cloud architects that were not considered a decade ago.
* Requirement Definition: It is crucial to use a standard template or checklist to define the requirements for these new technologies. This helps ensure that all necessary aspects are considered and that the technology is leveraged effectively to meet business needs.
* Business Alignment: Each list of requirements will differ based on the specific technologies and systems being defined, as well as how the business plans to leverage these technologies most effectively.
* Ongoing Journey: The process of understanding business requirements and mapping them to the right design decisions is an ongoing journey. Staying updated with new technologies and continuously refining your approach is fundamental to building valuable cloud-based systems.

## map storage

* Mapping Requirements: The process involves translating business requirements into technical attributes to choose the appropriate cloud storage solutions.
* Attributes to Consider: Key attributes include capacity, storage models (object, block, file), speed, disaster recovery, application interfaces, growth model, cost, management, and security.
* Multi-Cloud Deployment: It's common to use a mix of storage services from different cloud providers to support multi-cloud deployments.

## map compute
* Mapping Business Requirements: It involves translating business requirements into technical attributes to select the appropriate compute platform services from cloud providers.
* Key Considerations: Important factors include CPU type (e.g., Intel or AMD), memory size and speed, operating systems, disaster recovery options (active/active or active/passive), application interfaces, and security.
* Balancing Needs: It's crucial to find a cost-effective balance for memory and CPU to avoid oversizing or undersizing the compute power needed.

## map database
* Types of Databases: There are various types of databases, including traditional (e.g., Oracle, DB2), open-source (e.g., MySQL), and cloud-specific (e.g., AWS's DynamoDB).
* Considerations for Selection: Key factors include database capacity, type of data (text, images, video, etc.), database model (relational vs. object-based), speed, and management features.
* Database Security: It's important to consider data encryption and integration with broader security systems.

## map security 
* Security Tools and Technologies: Selecting the right security approaches and technologies is crucial. This includes encryption methods, identity and access management (IAM), and roles to manage users and systems.
* Governance: Governance works alongside security to place policies around the use of resources like applications, APIs, and storage. It ensures compliance with regulations and prevents misuse of sensitive data.
* Integration: Effective security and governance require integrating directories (e.g., Microsoft's Active Directory) to manage identities and provide a single source of truth.

