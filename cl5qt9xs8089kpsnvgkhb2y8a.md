## Teste de configuração

```javascript
const Button = (props: IButton) => {

  return (
    <button 
      onClick={props.onClick} 
      className={styles.Button}
    >
      <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M16 6V26" stroke="#020202" stroke-opacity="0.8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M26 16H6" stroke="#020202" stroke-opacity="0.8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      <p>{props.text}</p>
    </button>
  );
};

export default Button;
``` 
