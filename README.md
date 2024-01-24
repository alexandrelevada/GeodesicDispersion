# GeodesicDispersion
An iterative MCMC based fourth-order Runge-Kutta algorithm for numerical  simulation of Gaussian random fields' dynamics

ABSTRACT
Random fields are ubiquitous mathematical structures in physics, with applications ranging from thermodynamics 
and statistical physics to quantum field theory and cosmology. Recent works on information geometry of Gaussian 
random fields proposed mathematical expressions for the components of the metric tensor of the underlying
parametric space, allowing the computation of the Gaussian curvature in each point of the manifold that
represents the space of all possible parameter values that define such mathematical model. A key result in the 
dynamics of these random fields concerns the curvature effect, a series of variations in the curvature that happens
in the parametric space when there are significant increase/decrease in the inverse temperature parameter. 
In this paper, we propose a numerical algorithm for the computation of geodesic curves in the Gaussian random fields 
manifold by deriving the 27 Christoffel symbols of the metric required for the definition of the Euler-Lagrange equations. 
The fourth-order Runge-Kutta method is applied to solve the Euler-Lagrange equations using an iterative approach based in
Markov Chain Monte Carlo simulation. Our results reveal that, when the system undergoes phase trasitions, the geodesic
dispersion phanomenon emerges: the geodesic curve obtained by reversing the system of differential equations in time, 
diverges from the original geodesic curve, as we move from zero curvature configurations (Euclidean geometry) to negative 
curvature configurations (hyperbolic-like geometry). This phenomenon suggest that, time irreversibility in random field 
dynamics can be a direct consequence of the geometry of the underlying parametric space.
