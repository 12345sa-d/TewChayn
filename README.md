## About Me 🎋

```TypeScript
import { contact, IUser } from './github'

export default class ME implements IUser {
    public static firstName = 'Kevin'
    public static lastName = 'Antonio'
    public static username = 'TewChaynz'
    public static website = 'https://kevxnl.xyz'
    public static aliases = ['TewChaynz']
    public static skills = ['TypeScript', 'JavaScript', 'NodeJS', 'C', 'EJS', 'Express', 'NoSQL']
    public static info = {
        age: 21,
        country: 'Panama',
        org: 'None',
        likes: ['Nanatsu No Taizai', 'Well.....'],
        hobbies: ['Program', 'To Smoke', 'Music'],
        reach: [
            {
                name: contact.WhatsApp,
                url: 'https://wa.me/+50768666666?text=Well...'
            }
        ]
    }
    public static projects = [
        {
            name: 'tewfiles',
            homepage: 'https://github.com/tewfiles',
            repo: 'none',
            language: 'none',
            ongoing: true
        },
        {
            name: 'wa-sticker-tew',
            homepage: 'https://www.npmjs.com/package/wa-sticker-tew',
            repo: 'https://github.com/Tew-Chaynz/wa-sticker-tew',
            language: 'TypeScript',
            ongoing: true
        },
        {
            name: 'redirect-url',
            homepage: 'https://github.com/Tew-Chaynz/redirect-url#readme',
            repo: 'https://github.com/Tew-Chaynz/redirect-url',
            language: 'html',
            ongoing: true
        }
    ]
}


```
