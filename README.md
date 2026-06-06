# Basic usage - all stats visible (default)
/api/v1/user-stats.svg?userName=octocat

# Show only specific stats
/api/v1/user-stats.svg?userName=octocat&showCommits=false&showIssues=false

# Custom width
/api/v1/user-stats.svg?userName=octocat&width=600

# With custom theme
/api/v1/user-stats.svg?userName=octocat&theme=ocean

# Minimal stats display
/api/v1/user-stats.svg?userName=octocat&showHandle=false&showCommitsThisYear=false&showPRs=false&showIssues=false

# Custom animation speed
/api/v1/user-stats.svg?userName=octocat&animationDuration=4

# Hide the GitHub logo (widget becomes narrower at 300px)
/api/v1/user-stats.svg?userName=octocat&showLogo=false

# All parameters combined
/api/v1/user-stats.svg?userName=octocat&width=700&theme=midnight&animationDuration=3&showCommitsThisYear=false
