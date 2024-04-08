# CrewAI_Agent

CrewAI_Agent is an innovative project designed to streamline the process of planning and organizing trips. It leverages specialized agents and tasks to provide a comprehensive solution for travelers looking to optimize their journey experience.

## How It Works

The application operates around the `TripCrew` class, orchestrating the interaction between various travel agents and tasks to create a personalized trip plan:

- **Initialization**: The `TripCrew` class starts with travel details like origin, destination cities, travel dates, and interests.
- **Agent Setup**: Custom agents are created, including experts like an `expert_travel_agent`, `city_selection_expert`, and `local_tour_guide`.
- **Task Execution**: Tasks such as `plan_itinerary`, `identify_city`, and `gather_city_info` are carried out by the agents based on user input and preferences.
- **Crew Execution**: A `Crew` object comprising the defined agents and tasks collectively works to generate the travel plan.

## Usage

To use CrewAI_Agent, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/CrewAI_Agent.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CrewAI_Agent
   ```
3. Run the main script to start the trip planning process:
   ```bash
   python main.py
   ```

You’ll be prompted to enter your travel details, and the system will output a comprehensive travel plan.

## Acknowledgments

- Inspired by [CrewAI examples](https://github.com/joaomdmoura/crewAI-examples/tree/main).
- Thanks to "codewithbrandon" for the tutorial that helped develop this project.

## Conclusion

CrewAI_Agent automates travel planning with an intelligent system that adapts to user needs, simplifying the process and making efficient travel planning accessible to everyone.

## Disclaimer

This project is intended for educational and planning purposes only. Ensure to verify all travel details and arrangements independently before finalizing your travel plans. The authors and contributors of CrewAI_Agent are not responsible for any inaccuracies or issues that may arise from the use of this software.
