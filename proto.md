type="goal"
verifypositive="Application Confirmation"

type="action"
verifypositive="Find your perfect job"
action="search on automation jobs in london"

type="action"
verifypositive="Automation jobs in London"
action="view details of Gate Automation Engineer"

type="fail condition"
verifypositive="Gate Automation Engineer"
verifypositive="This is definitely a standard job"

type="retry condition"
retry="5"
action="get homepage"
verifypositive="Gate Automation Engineer"
verifypositive="Featured template is pending"

type="action"
action="get homepage"