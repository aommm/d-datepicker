derby-datepicker
================

Datepicker component for derby.js.

At the time being there is only an inline version. If you have any suggestions or improvements, open an issue or send a pull request!


Please note that this project is inspired by [Bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker), and makes use of a css-file from that project.


Example usage
=====

First of make sure to install derby-datepicker through npm `npm install derby-datepicker`.


Including
--------
    
    app.component(require('derby-datepicker'));
        
In template
-------
   
    <Body:>
      <datepicker active="{{post.date}}"></datepicker>
      
Retrieve data
--------

    var pickedDate = model.get('post.date');
