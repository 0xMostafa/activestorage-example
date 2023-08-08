# README

To Attach a image to user:

```ruby
user = User.create!(
  email: 'email@exmple.com',
  photo: { io: File.open('/path/to/file'), filename: 'file.png' }
)
```
