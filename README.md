```python
class WhoAmI:
    
    def __init__(self):
        self.user = 'Damir Karashev'
        self.current_work = "Pursuing a master's in AI"
        self.hobbies = [
            'Sketching',
            'Watching The Crown',
            'Preparing for the IELTS exam',
            'Being up all night wrestling with Xcode...'
        ]
    
    def get_city(self) -> str:
        return "Karaganda"
    
    def get_ambitions(self) -> list[str]:
        return [
            'Learn Korean',
            'Join Anthropic', 
            'See New York'
            # TODO: add 42 more awesome ambitions here ;)
        ]
```
