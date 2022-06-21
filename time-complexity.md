
# Time Complexity (21 June)
## Why learn Data structures and algorithms?
## Practice Problems
Arr = [1,2,3,4,5,6,7,8…..100]
Which is better O(N) or O(logN)? **ANS: O(logN)**

    int a = 0, b = 0;
    for (i = 0; i < N; i++) {
        a += 1;
    }
    for (j = 0; j < N; j++) {
        b += 1;
    }

**ANS: O(2N) or O(N)**

    int a = 0, b = 0;
    for (i = 0; i < N; i++) {
        a += 1;
    }
    for (j = 0; j < M; j++) {
        b += 1;
    }

**ANS: O(N+M)**

    int a = 0, b = 0;
    for (i = 0; i < N; i++) {
        for (j = 0; j < N; j++) {
            a = i+j;
        }
    }

**ANS: O(N^2)**

    int a = 0, i = N;
    while (i > 0) {
        a += i;
        i /= 2;
    }

**ANS: O(logN)**

## Next Session Question Link:
https://leetcode.com/problems/two-sum/

Try it with brute force and optimal solution. (Any Language)
