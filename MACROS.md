## Useful macros

### Hardline

`/hardline = kernel.hardline`

`/disconnect = kernel.hardline {{dc : true}}`

### Chat

`/chat = chats.send {{channel : "{0}", msg : "{$}"}}`

(there's nothing stopping you from making specialized chat scripts either!)

### Security

`/level = scripts.get_level {{ name: "{0}" }}`

## money

`/b = accts.balance`
