# algo-hw-09

This project compares the performance of two algorithms for finding the minimum number of coins needed to make a given amount: a greedy algorithm and a dynamic programming algorithm.

## Results

### Testing for amount: 113

- **Greedy Algorithm Result:** {50: 2, 10: 1, 2: 1, 1: 1}
- **Time taken:** 7.187001756392419e-06 seconds

- **Dynamic Programming Result:** {1: 1, 2: 1, 10: 1, 50: 2}
- **Time taken:** 8.589699427830055e-05 seconds

---

### Testing for amount: 1000

- **Greedy Algorithm Result:** {50: 20}
- **Time taken:** 2.972999936901033e-06 seconds

- **Dynamic Programming Result:** {50: 20}
- **Time taken:** 0.0006526790020870976 seconds

---

### Testing for amount: 10000

- **Greedy Algorithm Result:** {50: 200}
- **Time taken:** 1.8040009308606386e-06 seconds

- **Dynamic Programming Result:** {50: 200}
- **Time taken:** 0.007197207996796351 seconds

---

### Testing for amount: 50000

- **Greedy Algorithm Result:** {50: 1000}
- **Time taken:** 4.205998266115785e-06 seconds

- **Dynamic Programming Result:** {50: 1000}
- **Time taken:** 0.10843733100045938 seconds

---

## Conclusion

The greedy algorithm is generally faster but may not always provide the optimal solution. The dynamic programming algorithm guarantees the optimal solution but takes more time, especially for larger amounts.
