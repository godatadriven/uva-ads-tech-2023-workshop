# uva-ads-tech-2023-workshop
Repository for the AWS MLOps Workshop using SageMaker on 13th April 2023.


## Setup

Hi! Let's get you logged into the SageMaker Studio environment and start building pipelines.

1. Open up the AWS console:

    [https://116564700220.signin.aws.amazon.com/console](https://116564700220.signin.aws.amazon.com/console)

2. Login with your credentials:

    <img src="docs/aws-login-screen.png" width="300px" />

3. Open up SageMaker in the AWS console:

    <img src="docs/sagemaker-in-aws-console.png" />

4. Switch your region to **Ireland**.

5. Go to SageMaker **Domains** and click on the **playground** domain.

    ![](docs/domain-list.png)

6. Find the user which corresponds to your login i.e. **user-2**.

    ![](docs/user-filter-in-sm-domain.png)

    Then click Launch -> Studio. Give Sagemaker Studio a bit of time to launch:

    You should eventually see the Studio landing page:

    ![](docs/sm-studio-just-opened.png)

7. On the left-hand side, go to Git:

    ![](docs/git-clone-aws-studio.png)

    And then click **Clone a Repository**:
    
    ![](docs/clone-repo.png)

    Enter the following Git URL:

    ```
    https://github.com/godatadriven/uva-ads-tech-2023-workshop
    ```

8. Open up the `basic-pipeline.ipynb`:

    ![](docs/basic-pipeline.png)

9. Select the following for the environment on which the notebook will run:
    ![](docs/notebook-env.png)


10. Lastly, make sure to modify the username:

    ![](docs/modify-username-in-notebook.png)


Good luck! 🍀

## About
Created by Usman Zafar and Jetze Schuurmans, working for Xebia Data (formerly GoDataDriven).