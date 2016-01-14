# Twitter-js-tweet-delete

```javascript
jQuery('.js-stream-item').each(function(){
  var id = jQuery(this).data('item-id');
  jQuery.post(
    'https://twitter.com/i/tweet/destroy',
    {
      '_method':'DELETE',
      'authenticity_token':jQuery('.authenticity_token').val(),
      'id':id
    }
  );
});
```

Will coming with better js version later. + manual to using it.
