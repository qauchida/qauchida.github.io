A Better Way: A Lesson On What Not To Do

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
  profile: object;
}

class ExplorerInterestsWidget extends React.Component <IExplorerInterestsWidgetProps, IProfile> {
  constructor(props: any) {
    super(props);
    console.log(props);
  }
  ...
  
 private GenerateCourseRoute = (document) => {
    const variableSlug = Courses.findSlugByID(document._id);
    const username = this.props.match.params.username;
    const role = this.props.match.url.split('/')[1];
    const partialSlug = [];
    partialSlug.push(role);
    partialSlug.push(username);
    partialSlug.push('explorer');
    partialSlug.push('courses');
    partialSlug.push(variableSlug);
    const fullSlug = `/${partialSlug.toString().split(',').join('/')}`;
    return fullSlug;
  };
  ...
  }
  ```
  
  
