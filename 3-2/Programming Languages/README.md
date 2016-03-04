# Programming Language

## Course Info

* Instructor : 허충길
* Course Homepage : https://github.com/snu-sf-class/pl2016
* Course text : Software Foundations
* Practice Every week.

## COQ

### 수학의 로직

* Proof : Proposition
* ex) 1+1 = 2 이다 -> 증명
* = Element : Set
* 프로그래밍 언어에선 = Program : Type
* 기본적인 nat이나 plus, + 같은건 정의 되어있다.
* Type은 Set of all sets
* 증명의 존재함.

### Example

`````
Inductive nat : Type :=
| O : nat
| S : nat -> nat
.
`````

> O :  nat
>
> O가 nat이면 S(O)도 nat -> S(S(O)) 도 nat ...
>
> O를 0으로, S(0)을 1로 생각 ...
>
> 자연수가 정의되었다.

## Questions

* even에서 끝까지 돌려봐서 even 1이 false인지 확인하나?

> even 0는 0이 짝수라는 증명이 존재한다는 뜻.
>
> 2씩 더해가며 그다음 수가 짝수라는 것을 증명해나간다.
>
> 따라서 True. False 개념이 아니다.