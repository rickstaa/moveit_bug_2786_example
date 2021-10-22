# moveit_bug_2786_example

Simple example repository to show why bug [#2786](https://github.com/ros-planning/moveit/issues/2786#event-5504561867) is not a bug anymore and [#2928](https://github.com/ros-planning/moveit/pull/2928) was not needed.

## Instructions

1. Run `roslaunch moveit_bug_2786_example_repo main.launch moveit_controller_manager:=fake` and see that the `controller_list/type` parameter is correctly set.
2. Now run `roslaunch moveit_bug_2786_example_repo main.launch` see that no errors are thrown and the parameters are set correctly.
