- Each user can deploy a maximum of 10 namespaces.
- Each user can deploy a maximum of 10 metrics.
- Each user can create a maximum of 10 dimensions. Number of dimensions: number of original dimensions + number of aggregation dimensions. For example, a user specifies two metrics: diskusage and cpu_usage. The former contains dimensions ip and diskname, and the dimension ip is aggregated. The latter contains dimension cpu_name. In this case, the number of original dimensions and aggregation dimensions is 2 and 1 respectively, so there are 3 dimensions in total.
- There are only 5 dimensions under each metric.
- There are only 5 statistical methods under each metric.
- Only business data on Tencent Cloud's CVM is allowed to be reported.
- The data you reported will be retained for 30 days.
- An alarm rule corresponds to an alarm receiving group.
- CCM sends 1,000 alarm SMS messages to every developer each month.
