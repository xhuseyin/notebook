# css 

## Tailwind CSS vs Styled components in ReactJS

#### Styled components

```
const Wrapper = styled.div`
padding-bottom: 10px;
@media (min-width: 768px) {
    padding-bottom: 20px;
}
`;

const TestComponent = () => (
    <Wrapper>
        Hello world!
    </Wrapper>
);

```

#### TailwindCSS

```
const TestComponent = () => (
    <div className="pb-10 md:pb-20">
        Hello World!
    </div>
);

```

