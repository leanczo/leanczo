``` c#
using System;

namespace Leanczo
{
    class About : Me
    {
        public string[] GetCurrentWorkplace()
        {
            return new string[] { 
                "workplace" => 
                {
                    "company" => "Siltium",
                    "position" => "Backend Developer"
                }
            };
        }

        public string[] GetDailyKnowledge()
        {
            return new string[]
            {
                typeof(NetCoreCSharp).FullName,
                typeof(React).FullName,
                typeof(Angular).FullName,
                typeof(NestJS).FullName
            };
        }

        public string GetFutureGoal()
        {
            return "To make consistent contributions to the technology world.";
        }
    }
}


```
