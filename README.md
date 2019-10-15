# slurmio
Python tools to interface with slurm.

###Install with:
```bash
pip install slurmio
```

###Usage
```bash
>>> from slurmio.slurmio import SlurmJobParameters
>>> SlurmJobParameters().job_id
994986
>>> SlurmJobParameters().job_name
'bash'
>>> SlurmJobParameters().requested_cores
10
>>> SlurmJobParameters().allocated_cores
24
>>> SlurmJobParameters().requested_memory
10240 # in bytes
>>> SlurmJobParameters().allocated_memory
24576000000 # in bytes
>>> SlurmJobParameters().requested_nodes
1
>>> SlurmJobParameters().allocated_nodes
1
