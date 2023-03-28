# easy-polars-dataframes

fakedata --separator=, --limit=1000000 email country ipv4 ipv6 phone.code username name.first name.last state timezone >> data.csv (34 MB)
fakedata --separator=, --limit=8000000 email country ipv4 ipv6 phone.code username name.first name.last state timezone >> data.csv (160 MB)
time = 29s (1,2 GB)
fakedata --separator=, --limit=20000000 email country ipv4 ipv6 phone.code username name.first name.last state timezone color date >> data.csv (160 MB)
time = 29s (3,6 GB)

fakedata --separator=, --limit=30000000 email country ipv4 ipv6 phone.code username name.first name.last state timezone color date >> data.csv (160 MB)
time = 29s (7,7 GB)

=> perfect now I foudn the right size.