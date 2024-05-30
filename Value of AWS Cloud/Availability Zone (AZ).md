Each Region has multiple, isolated locations known as _Availability Zones_. The code for Availability Zone is its Region code followed by a letter identifier. For example, `us-east-1a`.

##### Steps to Ensure High Availability with AWS When launching an Instance:

^3813e4

1. **Select a Region and a VPC**:
    - Choose your preferred AWS Region.
    - Select a Virtual Private Cloud (VPC).

2. **Choose a Subnet**:
    - **Option 1**: Select a subnet from one of the Availability Zones.
    - **Option 2**: Let AWS choose a subnet for you.

3. **Distribute Instances**:
    - Spread your instances across multiple Availability Zones.
    - Design your application to handle failover:
        - If one instance fails, an instance in another Availability Zone can handle requests.

4. **Use Elastic IP Addresses**:
    - Mask the failure of an instance in one Availability Zone by:
        - Rapidly remapping the address to an instance in another Availability Zone.


![[region-with-azs.png]]