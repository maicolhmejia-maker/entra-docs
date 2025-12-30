
### Verify the instal
    * *Microsoft Entra private network connector updater* is an automated update service.
    * The updater checks for new versions of the connector and updates the connector as needed.

    ![Screenshot of the private network connector and connector updater services in Windows Services Manager.](media/how-to-configure-connectors/app-proxy-services.png)

1. If the status for the services isn't **Running**, right-click to select each service and choose **Start**.

## Create connector groups

To create as many connector groups as you want:

1. Browse to **Global Secure Access** > **Connect** > **Connectors**.
1. Select **New connector group**.
1. Give your new connector group a name, then use the dropdown menu to select which connectors belong in this group.
1. Select **Save**.

To learn more about connector groups, see [Understand Microsoft Entra private network connector groups](concept-connector-groups.md).



## Next steps

The next step for getting started with Microsoft Entra Private Access is to configure the Quick Access or Global Secure Access application:

* [Configure Quick Access to your private resources](how-to-configure-quick-access.md)
* [Configure per-app access for Microsoft Entra Private Access](how-to-configure-per-app-access.md)
