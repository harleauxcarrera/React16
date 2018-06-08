Lecture 40 Handling Events

   Used onClick insisde the button
   and defined a method called
   switch name handler

    Changing state with onClick
      Once state prop is defined insisde
      class based component, the method that gets
      ran for onClick will use the setState({})
      method built in to react
        this method overrides the old state with the new Once
        that is defined in the method



Lecture 43 Functional vs class components
  (stateless vs stateful)

  state and props are the two only thiings
  that can cause react to change the DOM

  Class based comps extend component
  Use function based comps as much as possible

  State should be controlled usually in only
  some comps includind app.js

Lecture 44

  methods can be passed as properties in components
  like click = {this.switchNamehandler} in app.js
  while the object file itsself has props.click
  (keep compoennts from having direct access to changing the state)

  Use the .bind() method to pass arugments to the methods being passed as properties
  An alternative to using the bind method to pass args to methods would be to use an
  arrow function when defining what action an event should take (onClick = {() => this.switchNamehandler('args')})

LEcture 45 two way binding

  here we learned how to change the name prop dynamically
  by using the onChange method in the component and having a nameChangeHandler method that takes an event as an
  arg,
  implemented where the state is changed . Particulary the name is now = event.target.value

Lecture 46 Adding stylesheets
  There are two ways to bust styling in react
    either using traditional class based styling
    or inline styles which require a render method that declares
    a const style property which is then passed as a prop to the component

    add styling to compoennts using their own .css file
    use className in the component instead of class
      import the css file into the component.js file
        adding CSS files to JS might seem wierd but webPack bundles the CSS
        and auto puts it into the html for us ( can be seen in the chrome inspector)
