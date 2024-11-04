## Source:

[My setup for solving LeetCode problems in Go (Golang)](https://www.youtube.com/watch?v=yKLTOQFcXsE&list=PLkS1-wgPo06-PW14bwcv_ETJFwaWZzKxm&index=45)

## Example - how create task and solution 

```shell
mkdir 1828-queries-on-point
touch $_/$_.go
```
### For example of .go file

```Golang
package LeetCode

func countPoints(points [][]int, queries [][]int) []int{
    return []int{}
}
```
### Make test files 

```shell
gotests -all -w - parallel 1828-queries-on-point/
```

### Go test manually 

```shell
go test ./1828-queries-on-point/1828-queries-on-point.go ./1828-queries-on-point/1828-queries-on-point_test.gotests
```

### Use gow

```shell
gow test 1828-queries-on-point/1828-queries-on-point.go 1828-queries-on-point/1828-queries-on-point_test.gotests
```


```shell
grc gow test 1828-queries-on-point/1828-queries-on-point.go 1828-queries-on-point/1828-queries-on-point_test.gotests
```


