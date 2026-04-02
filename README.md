```py
class Epsilon:
    def __init__(self):
        self.name="Ɛpsilon"
        self.site="3p5ilon.github.io"
        self.system=("macOS","Arch Linux")
        self.lang=("Python","TypeScript","JavaScript","C++","C")
        self.stack={
            "ml":("PyTorch","Transformers"),
            "backend":("FastAPI","gRPC"),
            "data":("PostgreSQL","Redis"),
            "infra":("Docker","Linux")
        }
        self.focus="applied ai systems"
        self.now=("llms","training","inference")

    def __repr__(self): return f"{self.name} :: {self.focus}"

if __name__=="__main__": print(Epsilon())
```
