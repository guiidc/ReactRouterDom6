# React Router Dom V6 Changes

Substitui o antigo history.push()
```
const navigate - useNavigate();
navigate('/minhaUrl')
```


Pegar parametros da URL dinâmica
```
const params = useParams();
console.log(params);
```

Pegar QueryString da Url
```
const [params] = useSearchParams();
console.log(params.get('chave da sua Query'));
```
