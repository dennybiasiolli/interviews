# Sales by Match

Alex works at a clothing store.
There is a large pile of socks that must be paired by color for sale.
Given an array of integers representing the color of each sock,
determine how many pairs of socks with matching colors there are.

For example, there are `n = 7` socks with colors `ar = [1, 2, 1, 2, 1, 3, 2]`.
There is one pair of color `1` and one of color `2`.
There are three odd socks left, one of each color. The number of pairs is `2`.


## Function Description

Create a `sockMerchant` function. It must return an integer representing
the number of matching pairs of socks that are available.

`sockMerchant` has the following parameter(s):

`n`: the number of socks in the pile
`ar`: the colors of each sock


## Constraints

- `1 <= n <= 100`
- `1 <= ar[i] <= 100` where `0 <= i < n`


## Output Format

Return the total number of matching pairs of socks that Alex can sell.


#### Sample Input

`n = 9`

`ar = [10, 20, 20, 10, 10, 30, 50, 10, 20]`


#### Sample Output

`3`


#### Explanation

![Socks](img/sales-by-match-01.png "Socks")

Alex can match three pairs of socks.
