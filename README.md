# bullhorn-fastlane
Send message to telegram with @bullhorn_bot on fastlane

## Usage Example
add this action on Fastlane script

    telegram(
    	url_horn: "https://integram.org/your_bot_code",
    	repo: ENV["GIT_REPO"],
    	branch: ENV["GIT_BRANCH"],
    	message: "Fastlane is OK"
    )
