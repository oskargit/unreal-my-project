# unreal-my-project

# build in tmp after checkout from github
# Linux
/home/oskar/work/gaming/Unreal/UnrealEngine/Engine/Build/BatchFiles/RunUAT.sh BuildCookRun -project="/tmp/unrealtest/unreal-my-project/MyProject.uproject" -noP4 -platform=Linux -clientconfig=Development -serverconfig=Development -cook -allmaps -build -stage -pak -archive -archivedirectory="/tmp/unrealtest/unreal-my-project/Build"
# Run
/tmp/unrealtest/unreal-my-project/Build/LinuxNoEditor/MyProject.sh

# Win64
/home/oskar/work/gaming/Unreal/UnrealEngine/Engine/Build/BatchFiles/RunUAT.sh BuildCookRun -project="/tmp/unrealtest/unreal-my-project/MyProject.uproject" -noP4 -platform=Win64 -clientconfig=Development -serverconfig=Development -cook -allmaps -build -stage -pak -archive -archivedirectory="/tmp/unrealtest/unreal-my-project/Build"
# Run
/tmp/unrealtest/unreal-my-project/Build/LinuxNoEditor/MyProject.sh

