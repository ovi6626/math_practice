집합
----
**집합(set)** 은 (집합의) **원소(element)** 라 불리는 대상의 모임 (집합은 근본적인 개념으로 정의할 수 없음 사용처마다 달라짐)
$x$가 집합 $A$의 원소이면 $x \in A$, $x$가 집합 $A$의 원소가 아니면 $x \notin A$라 쓴다.
> 여기서는 실수 집합은 $R$로 표기  

두 집합 $A$와 $B$의 원소가 일치하면 두 집합은 **같다(equal)** 고 하며 $A = B$ 라 표기한다.  
***
### 집합을 묘사하는 두가지 방법  
1. 중괄호 { } 사이에 집합의 원소를 나열
2. 집합의 원소가 가진 특징을 서술

1, 2, 3, 4를 원소로 하는 집합은 \{ $1, 2, 3, 4$ \}라 쓰거나 \{ $x:x는 5보다 작은 자연수$ \}라 쓴다.  

집합에서 원소가 배열되는 순서는 중요하지 않다.  
같은 원소를 여러 번 써도 집합이 변하지 않는다. 즉 \{ $1, 2, 3, 4$ \} $=$ \{ $3, 1, 2, 4$ \} $=$ \{ $1, 3, 1, 4, 2$ \}이다.  

`예제 1`  
1보다 크고 2보다 작은 실수를 원소로 포함한 집합 $A$는 $A =$ \{ $x\in R:1 < x < 2$ \}라 쓸 수 있다.  
***
집합 $B$의 모든 원소가 집합 $A$의 원소이면 집합 $B$를 $A$의 **부분집합(subset)** 이라 하고,  
$B \subseteq A$또는 $A \supseteq B$라 표기한다.  
`예시`  
\{ $1, 2, 6$ \} $\subseteq$ \{ $2, 8, 7, 6, 1$ \}이다.  

$B \subseteq A$이고 $B \neq A$인 집합 $B$를 $A$의 **진부분집합(proper subset)** 이라 한다.  
다음 사실은 두 집합이 같음을 보일때 자주 사용한다.
> $A = B \Leftrightarrow A \subseteq B$ 이고 $B \subseteq A$  

원소를 하나도 가지지 않는 집합을 **공집합(empty set)** 이라 하며, $\emptyset$으로 표기한다.  
공집합은 모든 집합의 부분집합이다.  
***
집합을 다른 집합과 결합시키는 기본적인 방법은 두 가지
1. 집합 $A$의 원소, 집합 $B$의 원소, 두 집합에 모두 속한 원소로 이루어진 집합을 $A$와 $B$의 **합집합(union)** 이라 하며 $A \cup B$으로 표기한다.  
   $A \cup B$ 를 다음과 같이 나타낼 수 있다.  
   $A \cup B =$ \{ $x:x\in A 또는 x \in B$ \}
2. $A$에도 속하고 $B$에도 속한 원소로 이루어진 집합을 $A$와 $B$의 **교집합(intersection)** 이라 하며 $A \cap B$으로 표기한다.  
   $A \cap B$를 다음과 같이 나타낼 수 있다.  
   $A \cap B =$ \{ $x:x \in A 이고 x \in B$ \}
> 두 집합의 교집합이 공집합이면 두 집합은 **서로소(disjoint)** 라 한다.  

`예제 2`  
두 집합 $A =$ \{ $1, 3, 5$ \}와 $B =$ \{ $1, 5, 7, 8$ \}에 대하여 합집합은 $A \cup B =$ \{ $1, 3, 5, 7, 8$ \}, 교집합은 $A \cap B =$ \{ $1, 5$ \}이다.  
비슷한 방식으로 $X =$ \{ $1, 2, 8$ \}과 $Y =$ \{ $3, 4, 5$ \}에 대하여 합집합은 $X \cup Y =$ \{ $1, 2, 3, 4, 5, 8$ \}, 교집합은 $X \cap Y = \emptyset$이다.  
따라서 $X$와 $Y$는 서로소이다.
***
두 개 이상의 집합의 합집합과 교집합은 비슷한 방법으로 확장 가능  
집합 $A_1, A_2,\cdots,A_n$의 합집합 $\underset{i=1} {\overset{n}\bigcup}A_i$ 와 교집합 $\underset{i=1} {\overset{n}\bigcap}A_i$ 는 각각 다음과 같이 정의한다.  
* $\underset{i=1} {\overset{n}\bigcup}A_i =$ \{ $x:$ 어떤 $i = 1,2,\ldots,n$에 대하여 $x \in A_i$ \}
* $\underset{i=1} {\overset{n}\bigcap}A_i =$ \{ $x:$ 모든 $i = 1,2,\ldots,n$에 대하여 $x \in A_i$ \}  

이때 각각의 $i \in$ \{ $1,2,\ldots,n$ \}마다 집합 $A_i$가 존재  
각각의 $A_i$는 집합 $I =$ \{ $1,2,\ldots,n$ \}으로 **색인(index)** 을 매겼다고 생각하면 편리  
이때 $I$를 집합족(collection) \{ $A_i:i \in I$ \}의 **색인집합(index set)** 이라 한다.  
색인 집합은 무한집합족(infinite collection)을 다룰 때 편리함  
$\Lambda$가 색인 집합이고 \{ $A_\alpha:\alpha \in \Lambda$ \}가 집합족(collection)일 때 이 집합의 합집합 $\underset{\alpha \in \Lambda} \bigcup A_\alpha$ 와 교집합 $\underset{\alpha \in \Lambda} \bigcap A_\alpha$ 는 각각 다음과 같이 정의한다.  
* $\underset{\alpha \in \Lambda} \bigcup A_\alpha =$ \{ $x:$ 어떤 $\alpha \in \Lambda$에 대하여 $x \in A_\alpha$ \}
* $\underset{\alpha \in \Lambda} \bigcap A_\alpha =$ \{ $x:$ 모든 $\alpha \in \Lambda$에 대하여 $x \in A_\alpha$ \}

`예제 3`  
색인 집합 $\Lambda =$ \{ $\alpha \in R:\alpha > 1$ \}과 각 $\alpha \in A$에 대하여 집합 $A_\alpha$를 $A_\alpha =$ \{ $x \in R:{-1 \over \alpha} \le x \le 1 + \alpha$ \}라 정의하면 다음이 성립  
* $\underset{\alpha \in \Lambda} \bigcup A_\alpha =$ \{ $x \in R:x > -1$ \}, $\underset{\alpha \in \Lambda} \bigcap A_\alpha =$ \{ $x \in R:0 \le x \le 2$ \}  
***
집합 $A$에서 정의된 관계는 $A$에 속한 임의의 원소 $x, y$에 대하여 $x$가 $y$와 연관되어 있는지 따지는 개념  
* $A$의 **관계(relation)** 는 $A$의 원소로 이루어진 순서쌍을 원소로 하는 임의의 집합 $S$이다.

집합 $A$의 원소 $x$와 $y$가 관계 $S$를 만족하기 위한 필요충분조건은 $(x, y) \in S$이다.  
$S$가 집합 $A$의 관계일 때, $(x, y) \in S$대신 $x \sim y$라 쓰기도 함  
실수 집합에서 두 수를 비교할때 사용하는 '같다', '미만', '이상'의 개념은 관계의 대표적인 예  

집합 $A$의 관계 $S$가 다음 세 조건을 만족하면 $A$의 **동치관계(equivalence relation)** 라 한다.
1. **반사성(reflexivity)** 모든 $x \in A$에 대하여 $x \sim x$이다.
2. **대칭성(symmetry)** $x \sim y$이면 $y \sim x$이다.
3. **추이성(transivity)** $x \sim y$이고 $y \sim z$면 $x \sim z$이다.  

`예시`  
$x \sim y$가 고정된 정수 $n$으로 나누어 떨어지는 것을 $x \sim y$라 정의하면 ~은 정수 집합에서 정의된 동치관계이다.
