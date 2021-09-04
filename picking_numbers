# problem- https://www.hackerrank.com/challenges/picking-numbers/problem

def pickingNumbers(a):
    # Write your code here
    m=0
    for i in a:
        c=a.count(i)
        d=a.count(i-1)
        c=c+d
        if c>m:
            m=c
    return m

if __name__ == '__main__':
    fptr = open(os.environ['OUTPUT_PATH'], 'w')

    n = int(input().strip())

    a = list(map(int, input().rstrip().split()))

    result = pickingNumbers(a)

    fptr.write(str(result) + '\n')

    fptr.close()
