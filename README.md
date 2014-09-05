BackboneDraftable
=================

A simple plugin that saves and retrieves a Backbone model's attributes into localStorage

##Usage

Invoke function eg: 

```
app.models.Message = Backbone.Model.extend({

  initialize: function() {
    Backbone.Draftable.call(this);
  }

});
```



