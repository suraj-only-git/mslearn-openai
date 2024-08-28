# Getting Started with Your Develop Generative AI solutions with Azure OpenAI Service

## Overall Estimated Duration: 60 minutes

## Overview

This lab introduces you to Azure OpenAI Service, a powerful platform that integrates OpenAI's generative AI models with the Azure cloud environment. Designed to introduce you to its core concepts and capabilities, this lab will guide you through provisioning a resource, deploying models, and interacting with various features. Learn to set up and configure an Azure OpenAI resource, deploy models, and experiment with the Completions and Chat playgrounds and acquire foundational skills in utilizing Azure's infrastructure for developing and refining AI-powered applications.

## Objective

By the end of this lab, you will be able to:

- **Provision and Configure Azure OpenAI Resources**: Set up and manage an Azure OpenAI resource, selecting appropriate settings such as region and pricing tier.

- **Deploy AI Models**: Deploy specific AI models within Azure OpenAI, including configuring deployment parameters to suit different application needs.

- **Utilize AI Model Features**: Experiment with various features of AI models, including generating text and code using the Completions and Chat playgrounds.

- **Explore and Refine Model Outputs**: Test and refine model responses by interacting with the AI models through practical exercises, understanding how different prompts and parameters affect outputs.

## Prerequisites

Participants should have: Basic knowledge and understanding of the following

- **Azure Portal**: For managing and provisioning Azure resources.
- **Azure AI Studio**: For deploying models and experimenting with their capabilities, including features such as the Completions and Chat playgrounds.

## Architecture

This architecture allows users to leverage Azure's cloud infrastructure to deploy and interact with advanced AI models. Through the Azure Portal, users manage their resources, while Azure AI Studio provides the tools needed to deploy and test these models. The Completions and Chat playgrounds within Azure AI Studio enable hands-on experimentation and refinement, facilitating the development of robust AI-powered applications.

## Architecture Diagram:

![](./media/lab-01-ad.png)

## Explanation of Components

**Azure Portal**: Central interface for provisioning and managing Azure OpenAI resources, including model deployment settings and resource configuration.

**Azure OpenAI Service**: Hosts and manages OpenAI models like GPT-35-Turbo, providing scalable access for tasks such as text completion and code generation.

**Azure AI Studio**: Interactive environment for deploying and experimenting with AI models. It includes the Completions Playground for generating text and the Chat Playground for simulating conversational interactions.

**Model Deployment**: Configures models with settings like deployment names and rate limits to ensure they meet application needs.

**Prompt and Parameter Exploration**: Involves crafting prompts and adjusting parameters (e.g., response length, randomness) to refine model outputs.

## Getting Started with the Lab

Once the environment is provisioned, a virtual machine (JumpVM) and lab guide will get loaded in your browser. Use this virtual machine throughout the workshop to perform the lab. You can see the number on the bottom of the Lab guide to switch to different exercises of the lab guide.
 
## Accessing Your Lab Environment
 
Once you're ready to dive in, your virtual machine and lab guide will be right at your fingertips within your web browser.
 
![Access Your VM and Lab Guide](./media/labguide-1.png)

### Virtual Machine & Lab Guide
 
Your virtual machine is your workhorse throughout the workshop. The lab guide is your roadmap to success.
 
## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment Details** tab.
 
![Explore Lab Resources](./media/env-1.png)
 
## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.
 
![Use the Split Window Feature](./media/spl.png)
 
## Managing Your Virtual Machine
 
Feel free to start, stop, or restart your virtual machine as needed from the **Resources** tab. Your experience is in your hands!
 
![Manage Your Virtual Machine](./media/res.png)

## Lab Validation

1. After completing the task, hit the **Validate** button under Validation tab integrated within your lab guide. If you receive a success message, you can proceed to the next task, if not, carefully read the error message and retry the step, following the instructions in the lab guide.

   ![Inline Validation](./media/inline-validation.png)

1. You can also validate the task by navigating to the **Lab Validation** tab, from the upper right corner in the lab guide section.

   ![Lab Validation](./media/lab-validation.png)

1. If you need any assistance, please contact us at labs-support@spektrasystems.com.

## Let's Get Started with Azure Portal
 
1. On your virtual machine, click on the Azure Portal icon as shown below:
 
   ![Launch Azure Portal](./media/sc900-image(1).png)
 
2. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:
 
   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>
 
       ![Enter Your Username](./media/sc900-image-1.png)
 
3. Next, provide your password:
 
   - **Password:** <inject key="AzureAdUserPassword"></inject>
 
       ![Enter Your Password](./media/sc900-image-2.png)
 
4. If prompted to stay signed in, you can click "No."
 
5. If a **Welcome to Microsoft Azure** pop-up window appears, simply click "Maybe Later" to skip the tour.
 
6. Click "Next" from the bottom right corner to embark on your Lab journey!
 
     ![Start Your Azure Journey](./media/sc900-image(3).png)

## Support Contact

The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels tailored specifically for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.

Learner Support Contacts:

- Email Support: labs-support@spektrasystems.com

- Live Chat Support: https://cloudlabs.ai/labs-support

Now, click on Next from the lower right corner to move on to the next page.

### Happy Learning!!