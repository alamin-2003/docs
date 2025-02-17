---
title: Gerenciar a exibição dos nomes de integrantes na organização
intro: Você pode permitir que integrantes da organização vejam o nome de perfil do autor de um comentário nos repositórios privados da organização.
product: '{% data reusables.gated-features.display-names %}'
redirect_from:
  - /articles/managing-the-display-of-member-names-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/managing-the-display-of-member-names-in-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Gerenciar exibição de nomes de integrantes
---

Proprietários de organização podem gerenciar a exibição do nome de integrantes na organização.

![Nome de perfil do autor do comentário exibido no comentário](/assets/images/help/issues/commenter-full-name.png)

Cada integrante da organização escolhe o próprio nome de perfil nas configurações. Para obter mais informações, consulte "[Personalizar seu perfil](/github/setting-up-and-managing-your-github-profile/personalizing-your-profile#changing-your-profile-name)".

{% ifversion profile-name-enterprise-setting %}
You may not be able to configure this setting for your organization, if an enterprise owner has set a policy at the enterprise level. Para obter mais informações, consulte "[Aplicar políticas de gerenciamento do repositório na sua empresa](/admin/policies/enforcing-policies-for-your-enterprise/enforcing-repository-management-policies-in-your-enterprise#enforcing-a-policy-for-inviting-outside-collaborators-to-repositories)".{% endif %}

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.member-privileges %}
5. Em "Admin repository permissions" (Permissões do administrador do repositório), marque ou desmarque **Allow members to see comment author's profile name in private repositories** (Permitir que integrantes vejam nome de perfil do autor nos repositórios privados). ![Caixa de seleção para permitir que integrantes vejam o nome completo do autor do comentário nos repositórios privados](/assets/images/help/organizations/allow-members-to-view-full-names.png)
6. Clique em **Salvar**.
