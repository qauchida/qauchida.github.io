A Better Way: A Lesson On What Not To Do
Take full advantage of TypeScript so that you can trim any redundancies in your code. 

Objective:
Find out how who is interested in an opportunity.

To Do That We Need:
- the User's Collection
- the ID of the opportunity



Here is a better way to do it:
```

interface IExplorerInterestsWidgetProps {
  type: string;
  match: {
    isExact: boolean,
    path: string,
    url: string,
    params: {
      username: string;
      interest: string;
    }
  }
  profile: IProfile;
  interest: IInterest;
}

private getObjectsThatHaveInterest = (profiles) => {
    const interested = [];
    _.map(profiles, (num) => {
      _.filter(num.interestIDs, (interests) => {
        if (interests === this.props.interest._id) {
          interested.push(num);
        }
      });
    });
    return interested;
  };
  
  
  const ExplorerInterestsWidgetCon = withTracker(({ match }) => {
  const username = match.params.username;
  const profile = Users.getProfile(username);
  const interest = Interests.findDoc(match.params.interst);
  return {
    profile,
    interest,
  };
})(ExplorerInterestsWidget);
```

