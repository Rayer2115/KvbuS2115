```typescript

class strikx {
  name : string
  dateOfBirth : string
  email : string

  constructor() {
    this.name = "Jakub Krzyżanowski"
    this.dateOfBirth = "2008-01-10"
    this.email = "jakub@fivestack.pl"
  }

  education() {
    return {
      '2022-now': 'Zespół Szkół Agrotechnicznych Nr. 5 w Słupsku (IT)'
    }
  }

  experience() {
    return {
      '2020-2023': 'Some discord bots (small projects)',
      '2021-2023': 'Small websites and web apps',
      '2023-now': 'Trying to get skills in frontend (bad ending)'
    }
  }

  skills() {
    return [ 'HTML', 'JAVASCRIPT', 'TYPESCRIPT', 'NODE.JS',
    'NPM/YARN', 'GIT', 'MySQL/MONGODB', 'DOCKER', 
    'LINUX SERVERS', 'WINDOWS SERVERS' ]
  }

  projects() {
  return []
  }
}

``````
