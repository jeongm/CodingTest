## 1에서 n까지의 합구하기
```python
def nsum(n):
    if n == 1:
        return 1
    else :
        return n + nsum(n-1)
        
if __name__ == '__main__':

  N = int(input())
  print(nsum(N))
```
