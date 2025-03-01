# DroneSecFS: Formal Methods for Optimized and Verified Drone Delivery Systems
 This project applies formal methods to address key challenges in drone delivery systems. It consists of two complementary components: (1) a path optimization solution that adapts the Traveling Salesman Problem to drone delivery using Answer Set Programming, and (2) a formal verification framework that models drone flight maneuvers using temporal logic (LTL/CTL). The path optimization balances distance and battery consumption to identify optimal delivery routes, while the formal verification ensures that drone flight behaviors satisfy critical safety and operational requirements. The implementation uses Potassco/clingo for ASP path optimization and NuSMV for model checking of temporal properties. This approach provides provable guarantees for drone delivery operations, balancing efficiency and safety in autonomous aerial logistics.
