# three-body-problem-simulation

A basic simulation of the gravitational three-body problem, where three masses interact under Newtonian gravity. <br>
This project is an educational tool to visualize chaotic orbits and experiment with different initial conditions.

### Running the Simulation

1. Clone the repository.
2. Open the project in your IDE.
3. Edit the `input.txt` file to set the masses, positions, and velocities for each body.
4. Run the main script

The simulation window will display the orbits and interactions of the bodies.

## Project Structure

- `input.txt` — Set initial mass, position, velocity, and acceleration for each body:
  
  ```
  mass, x-position, y-position, x-speed, y-speed, x-acceleration, y-acceleration
  ```

## Customization

- Change the number of bodies or their properties by editing `input.txt`.
- Adjust simulation parameters (such as time step or visualization settings) in the main script or relevant classes.
- Extend the code to add new forces, collision detection, or visualization improvements.

---

Note: This project is just a simple model for visualisation, there is no general closed-form solution to the three-body problem
