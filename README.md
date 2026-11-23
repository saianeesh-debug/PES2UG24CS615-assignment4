# VDUI Assignment 4

**Y Sai Aneesh Reddy · PES2UG24CS615**

[Read the assignment PDF](VDUI_Assignment_4_PES2UG24CS615.pdf) · [GitHub profile](https://github.com/saianeesh-debug) · [Project repository](https://github.com/saianeesh-debug/PES2UG24CS615-assignment4)

| Activity | Executed notebook | Input |
| --- | --- | --- |
| PPT 3 · Verify the AI analyst’s order claims | [Order analysis](PES2UG24CS615_Unit4_PPT3_Activity.ipynb) | [Orders CSV](freshkart_orders.csv) |
| PPT 4 · Audit ColdSense freezer alerts | [Freezer analysis](PES2UG24CS615_Unit4_PPT4_Activity.ipynb) | [Cold-chain CSV](freshkart_coldchain.csv) |

Open either notebook to see its results and charts. To reproduce them, keep the matching CSV beside the notebook and run all cells in Jupyter with Python 3, pandas, NumPy, SciPy, Matplotlib and scikit-learn installed.

Pune added 943 orders between Q2 and Q3. Two new stores accounted for 882 of them. ColdSense flagged 159 freezer-hours and correctly identified 16 of the 46 confirmed fault-hours at its default threshold.

The activities and synthetic datasets are adapted from [Deekshitha Marapareddy’s reference repository](https://github.com/DeekshithaMarapareddy/PES2UG24CS268-assignment4). This version corrects calculation and code errors and includes recomputed results and written responses.

[Orders pull request](https://github.com/saianeesh-debug/PES2UG24CS615-assignment4/pull/1) · [Freezers pull request](https://github.com/saianeesh-debug/PES2UG24CS615-assignment4/pull/2)
