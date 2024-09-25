This repository is fork from https://www.npmjs.com/package/responseFormater

Usage is similar, just customize response a little for personal using

The diffrent is the name of the package:

```
import responseFormater from 'response-formater'
import express, { Request, Response } from 'express'
const app = express()
const router = express.Router()
app.use(responseFormater) // add responseFormater middleware
app.use(router)

router.get('/hello', (req: Request, res: Response) => {
  res.send_badRequest('Request is wrong!')
})
```

# response-formater
