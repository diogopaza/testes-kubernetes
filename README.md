# testes-kubernetes

<h2>Comandos</h2>
<ul>
  <li>kubectl get nodes</li>
  <li>kubectl get pods</li>
  <li>kubectl apply -f nomeArquivo.yaml</li>
  <li>kubectl get pods -o wide == lista os pods com mais informcoes, alem das basicas</li>
</ul>

<h3>SVC</h3>
<p>Sao abstracoes para expor aplicacoes executando em um ou mais pods; proveem IP's fixos para comunicacao; sao capazes de fazer balanceamento de carga.</p>

<h4>ClusterIp - SVC</h4>
<p>Apenas para comunicao interna. </p>
