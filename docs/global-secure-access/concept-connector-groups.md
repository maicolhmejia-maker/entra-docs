

![Screenshot of application proxy where one app runs in an isolated IaaS virtual network with one connector group.](./media/concept-connector-groups/application-proxy-sample-config-2.png)

### Recommended configuration: Specific groups and a default idle group

For large, complex organizations, set the default connector group to hold idle or newly installed connectors. Don't assign applications to it. Serve all applications through custom connector groups.

In this example, the company has two datacenters (A and B). Two connectors serve each site. Each site runs different applications.

![Screenshot of a recommended setup with two datacenters, two connectors per site, a default idle connector group, and custom groups serving all applications.](./media/concept-connector-groups/application-proxy-sample-config-3.png)

## Related content

- [Microsoft Entra private network connectors](concept-connectors.md)
