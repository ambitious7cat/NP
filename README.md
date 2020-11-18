# P(polynomial-time)问题
能够在多项式时间内解决该问题，比如解决该问题的复杂度是n, n^2, n^3, n^4...
# NP(nondeterministic polynomial)问题
可以在多项式时间内验证某一个解是否正确
# NP = P？
P问题和NP问题有没有可能是同一个问题？是有可能的。NP问题中存在一类问题，只要这些问题能在多项式时间内解决，那么所有NP问题都是P问题，即NP=P，我们将此类问题称为NPC(complete)问题。
所有NP问题在多项式时间内都能约化到它的NP问题。
# NP-hard 问题
若将NPC问题中是NP问题的约束去掉，我们称其为NP-hard问题，也可以说NP-hard和NP的交集是NPC问题。NP困难问题“至少与NP完全问题一样难”，所有NP问题在多项式时间内都能约化到它的问题。
