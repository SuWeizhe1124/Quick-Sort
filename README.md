# Quick-Sort
快速排序(Quick Sort)
留言
快速排序是對泡沫排序的一種改進。通過一輪排序將要排序的數據分割成獨立的兩部分，其中一部分的數據都比另外一部分的數據要小，然後再按此方法對這兩部分數據分別進行快速排序，整個排序過程可以遞迴進行，以此達到整個數據變成有序。

基本思想
先從陣列中取出一個數作為基準數。
以基準數做分區，將比基準數大的數放到它的右邊，小於或等於它的數全放到它的左邊。
再對左右區間重複第二步，直到各區間只有一個數。
