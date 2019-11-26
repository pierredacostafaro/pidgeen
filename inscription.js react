import React, { Component } from 'react' ;


class Inscription extends Component {
  state= {
    first_name: null,
    last_name: null,
    email: null,
    password: null,
  };

  change = e => {
    this.setState({
      [e.target.id]: e.target.value
    });
  };


  submit = e =>{
    e.preventDefault();
    console.log(this.state);
  };

render() {
return ( < div >
  <form onSubmit={this.submit}>

  <label htmlFor="fname">First Name</label>
  <input type="text" id="name" onChange={this.Change}/>

  <label htmlFor="lname">Last Name</label>
  <input type="text" id="name" onChange={this.Change}/>

  <label htmlFor="email">Email</label>
  <input type="text" id="name" onChange={this.Change}/>

  <label htmlFor="mdp">Password</label>
  <input type="text" id="name" onChange={this.Change}/>

  <button>Sign up</button>
  </form>
  </ div > );
}
}
export default Inscription;
