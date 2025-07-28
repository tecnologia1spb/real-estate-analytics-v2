# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

- `npm i` - Instalar dependências
- `npm run dev` - Iniciar servidor de desenvolvimento com auto-reload
- `npm run build` - Build para produção
- `npm run build:dev` - Build em modo desenvolvimento
- `npm run lint` - Executar análise de código ESLint
- `npm run preview` - Preview do build de produção

## Project Architecture - MODERNIZADO ✨

Este é um dashboard de análise de portfólio imobiliário React TypeScript construído com Vite, **MIGRADO para Tremor UI** (biblioteca da Vercel), com integração Supabase otimizada e **localização completa em português brasileiro**.

### ⚡ Mudanças Recentes (Modernização 2025)
- **MIGRAÇÃO COMPLETA** de shadcn/ui para **Tremor UI** (v3.18.7)
- **Localização 100%** em português brasileiro
- **Web Workers** implementados para cálculos financeiros
- **Formatadores brasileiros** (moeda R$, datas dd/mm/yyyy)
- **Performance otimizada** com cálculos não-bloqueantes
- **Sistema holístico de prevenção de erros** implementado

### Tech Stack - ATUALIZADO
- **Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **UI Components**: **Tremor UI** (v3.18.7) - Biblioteca moderna da Vercel para dashboards
- **Styling**: Tailwind CSS v4 + configurações Tremor
- **State Management**: @tanstack/react-query v5 para estado do servidor
- **Database**: Supabase com TypeScript types
- **Charts**: **Tremor Charts** (otimizado para dashboards financeiros)
- **Routing**: React Router DOM
- **Performance**: **Web Workers** para cálculos analíticos
- **Localização**: date-fns/locale/pt-BR + formatadores brasileiros
- **Error Tracking**: Sistema preparado para Sentry com analytics local

## 🚀 NOVA IMPLEMENTAÇÃO: Framework AVA para Insights Automáticos (Janeiro 2025)

### ✅ AVA (Automated Visual Analytics) Integrado

A aplicação agora possui **inteligência artificial automatizada** para gerar insights financeiros usando a framework **@antv/ava** da Ant Design.

### 🛡️ Sistema de Qualidade e Prevenção de Erros (Janeiro 2025)

O projeto agora possui um **sistema completo de prevenção e correção de erros** que garante robustez e manutenibilidade:

#### 🔧 Ferramentas de Validação Automática
- **Script de Validação**: `npm run validate:imports` - Verifica imports de ícones Lucide React
- **Pre-commit Hooks**: Husky + lint-staged para validação antes de commits
- **Build Validation**: `npm run check:dashboard` - Validação + build completo

#### 🚨 Monitoramento Inteligente
- **Console Logging**: Detecção de erros via browser DevTools
- **Error Boundaries**: Captura inteligente de erros de componente
- **Contexto Detalhado**: Logs estruturados para debugging eficiente

### 🔍 Status de Verificação Supabase (Janeiro 2025)

**Data da Verificação**: 28/01/2025  
**Método**: UltraThink + MCP Supabase + Análise estrutural completa

**Resultados da Auditoria**:
- ✅ **Cliente Supabase**: Configurado e operacional
- ✅ **Conectividade**: Todas as 4 tabelas acessíveis e populadas
- ✅ **Hooks Modernos**: Todos os dashboards usando arquitetura atualizada
- ✅ **Performance**: Queries otimizadas com cache e paginação
- ✅ **Dados em Produção**: Shopping Park Botucatu com volume significativo

**Conclusão**: Sistema 100% funcional e alinhado com documentação.

## Controle de Versão e Branches 🚀

### Status do Projeto
- **Versão Atual**: v1.3.0 (Janeiro 2025)
- **Branch Principal**: `main` (código estável para produção)  
- **Branch de Desenvolvimento**: `develop` (desenvolvimento ativo)

### Histórico de Versões
- **v1.3.0** (28/01/2025): 
  - Sistema holístico de prevenção e correção de erros
  - Web Workers para analytics de alta performance
  - Error tracking preparado para Sentry
  - Modelos preditivos de ML implementados
  - Framework AVA para insights automáticos
  - Segundo repositório GitHub criado

### GitHub Repository
- **URL**: https://github.com/tecnologia1spb/real-estate-analytics-v2
- **Descrição**: Dashboard Avançado de Análise Imobiliária com IA
- **Status**: Público, com documentação completa

## Instruções Especiais para Desenvolvimento

- **Sempre responder em português do Brasil**
- **TodoWrite deve ser utilizado para documentar alterações**
- **Sempre trabalhar na branch develop para novas funcionalidades**
- **🔒 OBRIGATÓRIO: Executar `npm run check:dashboard` antes de push**
- **Sistema de qualidade ativo**: Validação automática de imports e ESLint