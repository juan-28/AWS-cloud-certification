---
id: Regions
aliases: []
tags: []
---

# Regions

- Each region is designed to be isolated from the other regions ^4c282f
- Achieves greatest possible fault tolerance and stability

**Resources:**
- When viewing resources, you see only the resources that are tied to the Region that you specified. This is because Regions are [[#^4c282f|isolated from each other]], and we don't automatically replicate resources across Regions.

When you launch an instance, you must select an AMI that's in the same Region. If the AMI is in another Region, you can copy the AMI to the Region you're using.

*Note that there is a charge for data transfer between Regions. For more information, see [Amazon EC2 Pricing - Data Transfer](https://aws.amazon.com/ec2/pricing/on-demand/#Data_Transfer).*
