# Prompt-design
This lab explores prompt engineering and best practices for designing effective prompts to improve the quality of your LLM-generated responses. You'll learn how to craft prompts that are concise, specific, and well-defined, focusing on one task at a time. The lab also covers advanced techniques like turning generative tasks into classification tasks and using examples to enhance response quality. For further exploration, refer to the official documentation on prompt design.

Prerequisites Before starting this lab, you should be familiar with:

Basic Python programming. General API concepts. Running Python code in a Jupyter notebook on Vertex AI Workbench. Objectives This lab will teach you how to:

Get started with prompt engineering using the Vertex AI SDK. Apply best practices for prompt design, including conciseness, specificity, and task definition. Explore various text generation use cases with the Vertex AI SDK, such as: Ideation Question answering Text classification Text extraction Text summarization Setup and requirements Before you click the Start Lab button Read these instructions. Labs are timed and you cannot pause them. The timer, which starts when you click Start Lab, shows how long Google Cloud resources will be made available to you.

This hands-on lab lets you do the lab activities yourself in a real cloud environment, not in a simulation or demo environment. It does so by giving you new, temporary credentials that you use to sign in and access Google Cloud for the duration of the lab.

To complete this lab, you need:

Access to a standard internet browser (Chrome browser recommended). Note: Use an Incognito or private browser window to run this lab. This prevents any conflicts between your personal account and the Student account, which may cause extra charges incurred to your personal account. Time to complete the lab---remember, once you start, you cannot pause a lab. Note: If you already have your own personal Google Cloud account or project, do not use it for this lab to avoid extra charges to your account. How to start your lab and sign in to the Google Cloud console Click the Start Lab button. If you need to pay for the lab, a pop-up opens for you to select your payment method. On the left is the Lab Details panel with the following:

The Open Google Cloud console button Time remaining The temporary credentials that you must use for this lab Other information, if needed, to step through this lab Click Open Google Cloud console (or right-click and select Open Link in Incognito Window if you are running the Chrome browser).

The lab spins up resources, and then opens another tab that shows the Sign in page.

Tip: Arrange the tabs in separate windows, side-by-side.

Note: If you see the Choose an account dialog, click Use Another Account. If necessary, copy the Username below and paste it into the Sign in dialog.

"Username"

You can also find the Username in the Lab Details panel.

Click Next.

Copy the Password below and paste it into the Welcome dialog.

"Password"

You can also find the Password in the Lab Details panel.

Click Next.

Important: You must use the credentials the lab provides you. Do not use your Google Cloud account credentials. Note: Using your own Google Cloud account for this lab may incur extra charges. Click through the subsequent pages:

Accept the terms and conditions. Do not add recovery options or two-factor authentication (because this is a temporary account). Do not sign up for free trials. After a few moments, the Google Cloud console opens in this tab.

Note: To view a menu with a list of Google Cloud products and services, click the Navigation menu at the top-left. Navigation menu icon Task 1. Open the notebook in Vertex AI Workbench In the Google Cloud console, on the Navigation menu (Navigation menu icon), click Vertex AI > Workbench.

Find the Workbench instance name instance and click on the Open JupyterLab button.

The JupyterLab interface for your Workbench instance opens in a new browser tab.

Task 2. Set up the notebook Open the notebook name file.

In the Select Kernel dialog, choose Python 3 from the list of available kernels.

Run through the Getting Started and the Import libraries sections of the notebook.

For Project ID, use Project ID, and for Location, use Region. Note: You can skip any notebook cells that are noted Colab only. If you experience a 429 response from any of the notebook cell executions, wait 1 minute before running the cell again to proceed. Click Check my progress to verify the objective. Install packages and import libraries.

Click Check my progress to verify the objective. Be concise.

Click Check my progress to verify the objective. Be specific, and well-defined.

Click Check my progress to verify the objective. Ask one task at a time.

Click Check my progress to verify the objective. Watch out for hallucinations.

Task 3. Reduce Output Variability Run through the Turn generative tasks into classification tasks to reduce output variability section of the notebook.

Click Check my progress to verify the objective. Generative tasks lead to higher output variability.

Click Check my progress to verify the objective. Classification tasks reduces output variability.

Task 4. Improve Response Quality by Including Examples Run through the Improve response quality by including examples section of the notebook.

Click Check my progress to verify the objective. Improve response quality by including examples.

Congratulations! In this lab you learned prompt engineering best practices using Generative AI with Google Gemini. You explored use cases which follow the best practices of being concise, specific, well-define, providing examples and asking one at a time when using LLMs to generate responses.

Next steps / learn more Check out the following resources to learn more about Gemini:

Gemini Overview Generative AI on Vertex AI Documentation Generative AI on YouTube Generative AI Official Repo Example Gemini Notebooks Google Cloud training and certification ...helps you make the most of Google Cloud technologies. Our classes include technical skills and best practices to help you get up to speed quickly and continue your learning journey. We offer fundamental to advanced level training, with on-demand, live, and virtual options to suit your busy schedule. Certifications help you validate and prove your skill and expertise in Google Cloud technologies.

Manual Last Updated October 18th, 2024

Lab Last Tested October 18th, 2024

Copyright 2025 Google LLC All rights reserved. Google and the Google logo are trademarks of Google LLC. All other company and product names may be trademarks of the respective companies with which they are associated.

Additional Comments
