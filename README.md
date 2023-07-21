``` c#
using System;

namespace Leanczo
{
    class About : Me
    {
        public object[] GetPublishedProjects()
        {
            return new object[]
            {
                new {
                    store = "Chrome Web Store",
                    projects = new string[] { "reddit-anon-ce", "coldplay-tc", "argentina-tc" }
                },
                new {
                    store = "Connect IQ Store",
                    projects = new string[] { "bayern-munich-wf", 
                                              "boca-jrs-wf", 
                                              "paris-saint-germain-wf", 
                                              "arsenal-wf", 
                                              "barcelona-wf", 
                                              "real-madrid-wf", 
                                              "argentina-wf",
                                              "inter-miami-wf",
                                              "u-de-chile-wf" }
                },
                new {
                    store = "Visual Studio Code Marketplace",
                    projects = new string[] { "blue-dollar-ve" }
                }
            };
        }
    }
}

```
