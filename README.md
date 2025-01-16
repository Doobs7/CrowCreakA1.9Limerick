# CrowCreakA1.9Limerick
An Example of a manager agent in crewai framework delegating tasks to different fruit experts for limericks on their given fruit.

Add api keys to .env.

Run on core_main.py.

Change the llm and the prompt on config.py.

TaskForceZero will run to create limericks on the different fruits.

TaskforceOne and TaskForceTwo have been commented out for this experiment but could be added into a flow with additional jobs.

When the process is complete the script will pause at a human_in_the_loop where someone can decide where to branch off (not set up in this example, just using as a  way to stop).

You will probably need to update the paths of the outputs which are currently at E:\Gangbusters\CyberMutantsProtoX1\CrowCreekA1.9 Limerick Poems\output\Poems. folder
