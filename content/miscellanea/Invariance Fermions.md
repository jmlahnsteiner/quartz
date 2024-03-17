## why Weyl fermions are Lorentz invariant
#calculations

for the pure fields
$$
\delta\varphi = \tfrac12\,\theta^{a}\gamma_a\varphi\qquad\delta\varphi^{\dagger}= \tfrac12\theta^a\varphi^\dagger\gamma_a
$$
and for the derivative operators
$$
\delta\dot{\varphi} = \tfrac12\theta^{a}\gamma_a\dot{\varphi}+ \theta^{a}\partial_{a}\varphi\qquad\delta\partial_{a}\varphi= \tfrac12\theta^{b}\gamma_b\partial_{a}\varphi + \theta_a\dot{\varphi}
$$
for the bilinears
$$
\delta\big(\varphi^{\dagger}\dot{\varphi}\big)= \theta^{a}\varphi^{\dagger}\gamma_a\dot{\varphi}+ \theta^a\varphi^\dagger\partial_a\varphi
$$
$$
\delta\big(\varphi^{\dagger}\gamma^{a}\partial_a\varphi\big)=\tfrac12\theta^{a}\varphi\big(\gamma_a\gamma_{b}+ \gamma_b\gamma_a\big)\partial^{b}\varphi+ \theta^a\varphi^\dagger\gamma_a\dot{\varphi}
$$
and at this point you just need to use $\gamma_a\gamma_b + \gamma_b\gamma_a = 2\,\delta_{ab}$ to see that
$$
\delta\big(\varphi^\dagger\dot{\varphi} - \varphi^\dagger\gamma^a\partial_a\varphi) = 0
$$
without any confusion about total derivatives or whatever.
