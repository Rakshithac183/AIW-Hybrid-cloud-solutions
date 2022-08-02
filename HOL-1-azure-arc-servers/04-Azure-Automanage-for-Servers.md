# HOL-1: Exercise 4: Enabling Azure Automanage for Server - Azure Arc

In the last exercise we had worked on onboarding SQL Server to Azure Arc, so now let's enable Azure Automanage for Server - Azure Arc which we have created earlier in the lab.

## Task 1: Configuring Azure Automanage

1. Navigate to home page of the [Azure Portal](https://portal.azure.com/#home), then search for **Automanage** in the search box and select **Automanage - Azure machine best practices**.

   ![](.././media/hol1-ex4-automanage-1.png "searchautoamanage")
   
2. From the Automanage pane, select **Automanage machines**(1) under Azure machine best practices and click on **+ Enable on existing machine**(2).

   ![](.././media/hol1-ex4-automanage-3.png "searchautoamanage")

3. On Enable Automanage - Azure machine best practices page, select **Azure best practices - Dev / Test** and click on **Select machines**.

   ![](.././media/hol1-ex4-automanage-4.png "searchautoamanage")

4. In Select machines pane, select the **ubuntu-k8s** Server - Azure Arc and click on **Select**.

   ![](.././media/hol1-ex4-automanage-5.png "searchautoamanage")

5. Click on **Enable**.

   ![](.././media/hol1-ex4-automanage-6.png "searchautoamanage")

6. Once the Configuration profile assignment completed successfully it will take around 20-30 minutes to get the Status as Conformant.

   ![](.././media/hol1-ex4-automanage-7new.png "searchautoamanage")

7. You can proceed with next task and review the status later.