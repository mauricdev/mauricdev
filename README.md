<?php

namespace Mauricdev;

class About extends BackendEngineer
{
    public function getEducation(): array
    {
        return [
            'Degree' => 'Ingeniería en Informática',
            'Institution' => 'Duoc UC',
            'Status' => 'Titulado'
        ];
    }

    public function getTechStack(): array
    {
        return [
            'Languages' => ['Java (8-21)', 'TypeScript', 'SQL', 'PL/SQL'],
            'Backend' => ['Spring Boot', 'Microservices', 'API REST'],
            'Cloud & DevOps' => ['GCP', 'Kubernetes', 'Docker', 'Jenkins', 'CI/CD'],
            'Tools' => ['SonarQube', 'Jira', 'Postman']
        ];
    }

    public function getCurrentFocus(): string
    {
        return 'Arquitecturas escalables, procesamiento masivo de datos y despliegue en la nube.';
    }

    public function getMotto(): string
    {
        return 'Si se puede imaginar, se puede programar y escalar.';
    }
}
