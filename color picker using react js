import React from "react";

export default class App extends React.Component {
  constructor(props) {
    super(props);
//sending parameters to parent class
    this.state = {
      red: 0,
      green: 0,
      blue: 0
    };
  }

  handlered = (event) => {
    this.setState({
      red: event.target.value
    });
  };

  handleGreen = (event) => {
    this.setState({
      green: event.target.value
    });
  };

  handleBlue = (event) => {
    this.setState({
      blue: event.target.value
    });
  };
  //this is a render function
  render() {
    return (
      <div
        style={{
          backgroundColor: "rgb(" + this.state.red + "," + this.state.green + "," + this.state.blue + ")",
          height: "100vh"
        }}
      >
        <div 
          style={{
            backgroundColor: "lightblue",
            borderRadius:600,
            width: 75,
            height: 250,
    
            padding: 60,
            
          }}
        >
          <h1>Color picker</h1>
          red :
          <input
            type="range"
            value={this.state.red}
            onChange={this.handlered}
          />
          <br />
          green :
          <input
            type="range"
            value={this.state.green}
            onChange={this.handleGreen}
          />
          <br />
          blue :
          <input
            type="range"
            value={this.state.blue}
            onChange={this.handleBlue}
          />
          <br />
        </div>
      </div>
    );
  }
}
