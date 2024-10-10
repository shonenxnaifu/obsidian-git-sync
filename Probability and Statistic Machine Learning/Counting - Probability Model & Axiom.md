# Counting
## Permutation
$$
n(n-1)(n-2) = n!
$$

$$
\frac{n!}{(n-k)!}
$$

## Combination
$$
_{n}C_{k} = \binom{n}{k} = \frac{n!}{k!(n-k)!}
$$
n = banyak element awal
k = banyaknya yang diambil

# Probabilistic Model

> model yang menjelaskan kondisi **uncertain** dengan lebih **sistematis**

Type:
- **Discrete**
- **Continues**
## Sample Space & Event
- **Random Experiment**: Proses obesrvasi pada sesuatu yang masih ***uncertain***
- **Sample Space**: 
	- **Kumpulan possible outcomes** yang mungkin terjadi dalam sebuah experiment
	- Syarat Sample Space:
		- **Mutually Exclusive**: Element harus unique
			- **Collectively Exhaustive**: apapun yang terjadi dalam **Experiment**, pasti akan **selalu mendapatkan outcome** di dalam **Sample Space** tersebut
		- **Right "Granularity"**: kondisi yang tidak mempengaruhi sample space tidak perlu dimasukkan
	Exp:
	![[Screenshot 2024-10-10 at 3.02.11 PM.png]]
- Event: 
	- Kejadian yang terjadi dalam sample space
	- Tidak terbatas hanya 1 event saja (bisa multiple)
### Probabilty Formula
$$
P(A) = \frac{n(A)}{n(Ω)}
$$
P(A) = Probability dari suatu event
n(A) = Banyak anggota kejadian di event A
n(Ω) = Banyak anggota kejadian di sample space
#### ada 2 cara
##### Probability Formula

$$
\frac{\text{Banyak anggota kejadian di Event}}{\text{Banyak anggota Kejadian di Sample Space}}
$$
- in assumption outcomes are equally  likely to happen
- discrete uniform probabilty law
- theoretical probability

##### Probabilty as Relative Frequency
$$
\frac{\text{Banyak percobaan dimana kejadian A terjadi}}{\text{Banyak seluruh percobaan}}
$$
- no assumption about outcomes
- need simulation or data
- relative frequency
## Axiom of Probability
- Non Negativity: P(A) ≥ 0
- Normalization: P(Ω) = 1
- Additivity: P(A<sub>1</sub> ∪ A<sub>2</sub> ∪ ...) = P(A<sub>1</sub>) + P(A<sub>2</sub>) + ...
