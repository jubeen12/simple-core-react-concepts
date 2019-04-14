# simple-core-react-concepts


1.copy https://github.com/jubeen12/simple-core-react-concepts/blob/master/App.html

2.create component as a class has a render().


	class Hello extends React.Component {
    render() {
        return <h1>Hello {this.props.message}!</h1>;
    }
}


3. use ReactDOM.render to render app. it coonects to root id

		ReactDOM.render(
   	<Hello message="my friend" />, 
  	 document.getElementById("root")
	);

4.It Draws Hello my friend! to App.html
