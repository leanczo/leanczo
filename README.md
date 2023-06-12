``` c#
namespace Leanczo;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Siltium', 
                'position' => 'Backend Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            NetCoreCSharp::class,
            React::class,
            Angular::class,
            NestJS::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To make consistent contributions to the technology world.';
    }
}

```
