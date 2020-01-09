## IBM Cloud Stencils for PowerPoint

![VPCFull](/images/vpc-experience-full-powerpoint.png)

# Implementation Notes

1. VPC stencils for PowerPoint consists of:
    1. VPC Icons
    2. VPC Groups
    3. Other IBM Icons
2. VPC Groups includes the group tag (square icon in upper left corner) with the group border and also includes a few enhancements for consumability and readability.
3. Group name (e.g. IBM Cloud) can be deleted if desired if you want the group tag alone to identify the group.
4. Group tag can be deleted if desired.
5. Borders are solid and 2 pt to be visible with limited space except Security Group is dashed - can be customized as desired.
6. Lines are black to distinguish from borders and icons - can be customized as desired.
7. Text is black and Helvetica 12 pt - can be customized as desired.
8. VPC Icons include a standard version of networking icons by request such as load balancer, public gateway, VPN gateway, etc.  Other IBM icons for the same functionality may also be available such as the load balancer icon under Infrastructure.

# Upgrade Steps

To update an existing diagram to the latest version on this github for PowerPoint:
1. Open VPCv2 PPT (all-ibm-cloud-architecture-icons-October2019-VPCv2UpdatesJanuary2020.pptx): 
2. Backup existing diagram and open existing diagram in PowerPoint.
3. For each VPC group in diagram compare to VPC v2 PPT:
    1. For each Subnet group move contents of ACL textbox to Subnet textbox, see example.
    2. For each group border set border color and 2 pt width to match same in VPCv2 PPT.
    3. For each Zone and Subnet set fill color to match same in VPCv2 PPT.
    4. For each Region and Zone replace the group tag to match same in VPCv2 PPT.
4. Increase lines to 2 pt for visibility.
5. If Cloud Universe group was used you can either leave as is or replace with the Public Network and Enterprise Network groups in VPCv2 PPT.
6. Tweek the diagram if more space is needed.

Return to [README](/README.md)